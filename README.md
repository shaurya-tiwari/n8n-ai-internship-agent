<p align="center">
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/automation/automation.png" width="120" />
</p>

<h1 align="center">🤖 AI Internship Agent</h1>

<p align="center">
  <b>Resume-based autonomous AI agent that finds relevant internships and delivers them to Telegram.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/n8n-automation-orange" />
  <img src="https://img.shields.io/badge/Gemini-AI-blue" />
  <img src="https://img.shields.io/badge/Telegram-Bot-success" />
  <img src="https://img.shields.io/badge/Status-Working-green" />
</p>

---

## 🚀 Overview

**AI Internship Agent** is an autonomous AI system built using **n8n** that:

- Understands a resume using **Gemini AI**
- Dynamically determines suitable internship roles
- Generates smart, filtered internship search links
- Sends curated opportunities directly to **Telegram**
- Runs on a single trigger (`/start`) with no hard-coded logic

This project is designed as a **portfolio-grade AI agent**, not just a bot.

---

## ✨ Features

| Feature | Description |
|------|------------|
| Resume Understanding | Uses Gemini AI to extract roles & skills |
| Autonomous Decisions | No hard-coded roles |
| Smart Filtering | Remote, Part-time, Delhi / Noida / GN |
| Telegram Trigger | `/start` command runs the agent |
| One-click Execution | No UI interaction required |
| AI Agent Architecture | Reason → Decide → Act |

---

## 🧠 How the AI Agent Works

Telegram (/start)
↓
Resume Analysis (Gemini AI)
↓
Role & Skill Reasoning
↓
Dynamic Internship Search Strategy
↓
Formatted Results
↓
Telegram Notification


---

## 🛠️ Tech Stack

| Tool | Purpose |
|----|--------|
| n8n | Workflow orchestration |
| Gemini AI | Resume understanding & reasoning |
| JavaScript | Dynamic logic & link generation |
| Telegram Bot API | User interaction |
| Render / n8n Cloud | Deployment |

---

## 📂 Project Files

| File | Description |
|----|------------|
| `ai-internship-agent-n8n.json` | Main n8n workflow |
| `README.md` | Project documentation |

---

## ⚙️ Setup Guide

1. Import the workflow JSON into n8n
2. Configure:
   - **Gemini API key** (as credential / env variable)
   - **Telegram Bot Token**
3. Activate the workflow
4. Open Telegram → send `/start`
5. Receive internship links automatically

---

## 📬 Sample Output
🔥 Fresh Internship Matches (Resume-Based)

AI/ML Engineer Intern
👉 https://internshala.com/
...

Frontend Developer Intern
👉 https://internshala.com/
...

✨ Tip: Sort by “Recently posted” & apply fast



---

## 🎯 Use Cases

- Students & freshers
- AI-driven job discovery
- Automation portfolio project
- No-code / low-code AI agent demos

---

## 🔮 Future Enhancements

- Daily scheduled alerts
- Duplicate internship filtering
- Application tracking (Google Sheets)
- Google Jobs integration
- Multi-command Telegram bot (`/remote`, `/parttime`)

---

## 👨‍💻 Author

"SHAURYA TIWARI"
AI & Automation Enthusiast  
Built as a personal AI agent project 🚀

