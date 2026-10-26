<div align="center">

# Yazan Hamdi
### Full Stack AI Engineer | Jordan 🇯🇴

*I build AI-powered systems that run real businesses: accounting, fleet, retail, and customer support.*

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:YAZANHAMDE559@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-yazanhamde-181717?style=flat&logo=github)](https://github.com/yazanhamde)

</div>

---

## About Me
- 🎓 B.Sc. Administrative Information Systems — Al-Balqa Applied University
- 🤖 Specialized in **AI, Computer Vision & LLM Applications**
- 🏭 Build and ship **production systems** used daily by real businesses (not demos)
- 💼 Delivered **10+ graduation projects** for university students
- 🌍 Open to relocation in the **Gulf region**
- 📜 IELTS Certified

---

## 🛠️ Tech Stack

**AI & ML:** Python · OpenAI API (GPT-4o-mini, Whisper, Embeddings) · RAG · LangChain · LangGraph · YOLOv8 · OpenCV

**Backend:** PHP · Python (FastAPI, discord.py, PyQt5) · REST APIs · Webhooks · Cron jobs

**Database:** MySQL · SQLite · SQL (schema design, migrations)

**Frontend:** JavaScript · HTML · CSS · Progressive Web Apps (PWA)

**Integrations:** WhatsApp Cloud API · Facebook Messenger · Instagram · Discord · Telegram · GPS tracking · ESC/POS printers

---

## 🚀 Key Projects

| Project | Tech |
|---------|------|
| 🛡️ AI Theft Detection System | YOLOv8 · Python · Telegram API |
| 🤖 Full Social Media AI Agent | LangChain · LangGraph · RAG · PHP |
| 📊 Enterprise Accounting ERP + AI Assistant | PHP · MySQL · OpenAI · WhatsApp Cloud API |
| 💬 Multi-Channel AI Sales Agent (WhatsApp / Messenger / Instagram) | PHP · OpenAI · RAG · Meta APIs |
| 🚗 Fleet & HR Tracking System | PHP · MySQL · GPS · PWA |
| ☕ Offline Coffee Shop POS | Python · PyQt5 · SQLite · ESC/POS |
| 🎮 GamerGuard — AI Moderation Bot for Gaming Communities | Python · discord.py · OpenAI · FastAPI |

---

## 📌 Featured Work

<details open>
<summary><b>📊 Enterprise Accounting ERP + Arabic AI Assistant</b></summary>

A full accounting system for a trading business, with a conversational assistant that turns plain Arabic messages into validated accounting entries.

- **59-table MySQL schema** covering customers, suppliers, banks, cash, payroll (employees & drivers), a workshop module, tax reports, and profit analysis
- **Natural-language entry:** the owner types or speaks ("paid the supplier 200 from cash"), the LLM returns structured JSON actions, the system asks for confirmation, executes, and supports undo
- Understands local business slang and asks clarifying questions instead of guessing when a bank or account is ambiguous
- **Receipt/invoice image analysis** and **voice input** (Whisper)
- **Official WhatsApp Cloud API integration**: signed webhook verification, duplicate-message protection, owner-number allowlist
- **POS synchronization** with idempotent imports and an opening-balance cutoff to prevent double counting
- PDF and Excel export, scheduled reminders, and migration scripts for safe upgrades

**Stack:** PHP · MySQL · OpenAI · WhatsApp Cloud API · Cron

</details>

<details>
<summary><b>💬 Multi-Channel AI Sales & Support Agent</b></summary>

An AI agent that answers customers on **WhatsApp, Facebook Messenger, and Instagram Direct** through one unified webhook, with a management dashboard for the business owner.

- **RAG memory:** the agent learns from corrected answers (embeddings with `text-embedding-3-small`), plus a knowledge base, product search, and colloquial product-name aliases
- **Human handoff:** pause/resume the bot per conversation or globally, owner alerts, and live conversation view
- Order capture, customer drop-off reports, and monthly performance reports
- Handles customer photos, with an "unresolved images" queue for staff to label
- Installable **PWA dashboard** (service worker, offline shell)

**Stack:** PHP · OpenAI · RAG · Meta Graph APIs · JavaScript PWA

</details>

<details>
<summary><b>🚗 Fleet & HR Tracking System</b></summary>

A unified operations platform for a company with drivers and field staff.

- **Live GPS trip tracking** and location alerts for drivers
- **Attendance** with location capture, shifts, leave management, overtime requests, and manager force-checkout
- Employee performance reports, notes, and notifications
- Integrated **warehouse/inventory module** with role-based permissions (employee / driver / admin)
- **30-table MySQL schema**, REST API layer, scheduled jobs, and an installable PWA for field use
- Arabic RTL interface

**Stack:** PHP · MySQL · GPS · PWA · Cron

</details>

<details>
<summary><b>☕ Offline Coffee Shop POS</b></summary>

A complete point-of-sale desktop application designed for a real shop running **Windows 7** with no internet dependency.

- **Cashier screen** with categories, product options/add-ons (size, milk type), cart, tax, and manager-only discounts
- **Shift management:** opening cash, closing, and automatic expected-vs-actual cash variance
- **Role-based access** (manager / cashier) with per-user salted password hashing and forced password change on first login
- **ESC/POS receipt printing** (Arabic code-page support) and cash-drawer control
- **Recipe-based inventory:** stock is deducted automatically on each sale; suppliers, purchases, and expenses tracked
- Daily/monthly/cashier-performance **reports** with Excel export
- **Audit log** for every sensitive action and **automatic daily backups** (rolling 30 copies)
- 20-table SQLite schema, packaged to a standalone `.exe` with PyInstaller (Python 3.8 for Win7 compatibility)

**Stack:** Python · PyQt5 · SQLite · ESC/POS · PyInstaller

</details>

<details>
<summary><b>🎮 GamerGuard — AI Moderation & Matchmaking for Arabic Gaming Communities</b></summary>

A Discord bot plus a web admin panel that keeps gaming servers safe and helps players find teammates.

- **Cost-aware two-stage moderation:** every message goes through a free moderation filter first, and the LLM is called only on borderline cases, with the last few messages as context. First offence = private warning, repeats = alert to moderators. **No auto-bans** (a human always decides)
- **Looking-for-group system:** interactive wizard with buttons and menus, filters by game, rank range, age, and reputation, with temporary voice channels created automatically
- **Player reputation:** `/report`, `/rate`, `/profile`, built from community ratings and moderation history
- **Auto-translation** between community languages and voice-message handling
- **Admin dashboard (FastAPI):** role-based accounts (admin / moderator), report queue, player history and private notes, full **audit log**, forced password rotation, instant session revocation, per-server settings
- **Privacy-minded:** `/privacy` command and configurable data-retention window

**Stack:** Python · discord.py · OpenAI API · FastAPI · SQLite (async)

</details>

---

## 🧭 How I Work
- **Ship to real users:** every system above runs (or ran) in an actual business with real data
- **Security basics by default:** hashed credentials, forced password changes, role-based permissions, audit logs, webhook signature checks
- **AI with guardrails:** structured outputs, human confirmation for financial actions, human handoff for customer chats, and cost control for LLM calls

---

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=yazanhamde&show_icons=true&theme=tokyonight&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=yazanhamde&layout=compact&theme=tokyonight&hide_border=true)

</div>
