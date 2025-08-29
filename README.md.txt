# 🤖 Ultimate AI Agent (n8n + Multi-Agent System)

This is a **modular AI-powered personal assistant** built inside [n8n](https://n8n.io).  
It orchestrates multiple specialized agents for email, calendar, contacts, and content creation.

## 🚀 Features
- **Email Agent** → Gmail send, draft, reply, labels.
- **Calendar Agent** → Create, update, delete events in Google Calendar.
- **Contact Agent** → Manage contacts in Airtable.
- **Content Creator Agent** → Generate SEO-friendly blog posts (Tavily + LLM).
- **Parent Orchestrator** → Routes tasks to the right agent, keeps context, supports text + voice via Telegram.

## 📂 Project Structure
Ultimate AI Agent/
│
├── agents/
│ ├── __Calendar_Agent.json
│ ├── __Contact_Agent.json
│ ├── __Content_Creator_Agent.json
│ ├── __Email_Agent.json
│ └── Ultimate_Personal_Assistant.json
│
├── .gitignore
├── README.md

## 🛠️ Setup
1. Import each `.json` workflow into **n8n**.
2. Add credentials:
   - Gmail (Email Agent)
   - Google Calendar (Calendar Agent)
   - Airtable (Contact Agent)
   - Tavily (Search + Content)
   - Telegram (interaction)
3. Start the **Ultimate Assistant** workflow and interact with it.

---
