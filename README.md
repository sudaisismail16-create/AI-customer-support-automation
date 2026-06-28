# 🤖 AI Customer Support Automation

An automated customer support system built with Make.com, Groq AI (LLaMA 3.3), Gmail, and Google Sheets. The system automatically classifies incoming support tickets and generates professional email replies without any human intervention.

---

## 📌 Overview

This project automates the entire customer support workflow:
- Customer submits a support request via Google Form
- AI classifies the issue into a category (Billing / Technical / General)
- AI generates a professional email reply tailored to the issue
- Customer receives an automatic reply via Gmail
- All interactions are logged in Google Sheets with timestamps

---

## 🔧 Tech Stack

| Tool | Purpose |
|---|---|
| Make.com | Automation platform / workflow builder |
| Groq AI (LLaMA 3.3-70b) | Issue classification and reply generation |
| Google Forms | Customer support ticket intake |
| Gmail | Automated email replies |
| Google Sheets | Logging and analytics |

---

## 🔄 Workflow

```
Customer fills Google Form
        ↓
Make.com triggers automatically
        ↓
Groq AI classifies the issue
(Billing / Technical / General)
        ↓
Groq AI generates professional reply
        ↓
Gmail sends reply to customer
        ↓
Google Sheets logs everything
(Name, Email, Issue, Category, AI Reply, Timestamp)
```

---

## ✨ Features

- **Auto Classification** — AI reads the message and categorizes it instantly
- **AI Reply Generation** — LLaMA 3.3 writes a professional reply tailored to the issue type
- **Instant Email Response** — Customer receives a reply within minutes of submitting
- **Full Logging** — Every ticket is logged with category, reply, and timestamp
- **Runs 24/7** — Scenario runs every 15 minutes automatically, no human needed

---

## 📊 Google Sheets Log Structure

| Name | Email | Issue Type | Message | AI Category | AI Reply | Timestamp |
|---|---|---|---|---|---|---|
| Ahmed Ali | ahmed@gmail.com | Billing | My bill was charged twice | Billing | Dear Customer... | 28/06/2026 15:03 |

---

## 💡 What I Learned

- Building multi-step automation workflows in Make.com
- Integrating AI APIs (Groq / LLaMA) via HTTP POST requests
- Handling nested JSON data mapping
- Combining multiple Google services in one pipeline
- Prompt engineering for consistent AI outputs

---

## 👤 Author

**Hafiz Sudais Ismail**  
CS Student — Information Technology University, Lahore  
bscs25024@itu.edu.pk

---

> Built during holiday break as part of learning AI automation with Make.com
