# 💼 job_notifier — AI-Powered Job Alert Agent

job_notifier is an autonomous AI agent built using [n8n](https://n8n.io/) that monitors remote job listings and sends you curated job opportunities directly on Telegram. It uses AI to clean job data and notify you with key job info like title, company, description, and application link.

---

## ✨ Features

- 🔍 Scrapes remote jobs from platforms like *RemoteOK* or *Remotive*
- 🤖 Uses *OpenAI or HuggingFace* to clean HTML and format descriptions
- 📬 Sends clean job listings to *Telegram* with:
  - Job title  
  - Company name  
  - Short description (cleaned from HTML)  
  - Direct apply link
- ⏱ Fully automated on a *schedule (Cron)* — runs every 15–30 minutes

---

## 🔧 Requirements

- [n8n](https://n8n.io/) self-hosted or cloud version
- Telegram Bot Token and Chat ID
- OpenAI API Key (or alternative like HuggingFace/Groq)
- Optional: Vector DB (for long-term memory)

---

## 🧠 Architecture Overview
