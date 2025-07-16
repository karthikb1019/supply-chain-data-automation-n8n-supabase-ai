# 📦 Supply Chain Data Automation using n8n, Supabase & Quadratic AI

This project automates end-to-end supply chain reporting by integrating Gmail-triggered sales files with n8n workflows, storing data in Supabase PostgreSQL, and generating AI-powered KPIs using Quadratic AI.

---

## 📽️ Project Demo

👉 Watch the full Loom demo here:  
[![Watch on Loom](https://cdn.loom.com/sessions/thumbnails/5d5d07df8b1448b29904cd15b839599d-with-play.gif)](https://www.loom.com/share/5d5d07df8b1448b29904cd15b839599d?sid=234542a8-8af0-4dc4-98a0-5bdb904a379f)

---

## 📌 Key Features

- ✅ Gmail Label Trigger for daily sales data
- ✅ CSV parsing and schema mapping using n8n
- ✅ Automated inserts into Supabase PostgreSQL (Star Schema)
- ✅ AI-driven prompts in Quadratic AI for:
  - `dim_date` table generation
  - Exchange rate extraction via OpenExchangeRates API
  - KPI calculations for supply chain insights
- ✅ No-code and low-code driven pipeline

---

## 🛠️ Tech Stack

- **n8n** – No-code workflow automation  
- **Supabase** – Cloud PostgreSQL backend  
- **Quadratic AI** – Prompt-based analytics platform  
- **Google Cloud OAuth** – Gmail API setup  
- **Open Exchange Rates** – Currency rate API  

---

## 📂 Repository Structure

```bash
├── workflow/         # n8n JSON export
├── database/         # Supabase schema + table docs
├── prompts/          # All AI prompts used in Quadratic
├── assets/           # Screenshots, diagrams
├── LICENSE
└── README.md
