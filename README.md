# 💸 Personal Expense Tracker (n8n Workflow)

This is an **n8n automation workflow** that converts Discord messages into structured expense logs.  
When a message is sent in your personal Discord channel, n8n parses it with an LLM (via Ollama or OpenAI), and records the result in Google Sheets.

## ✨ Features
- Parse natural-language expense messages from Discord
- Convert them into structured JSON data
- Log entries automatically into a Google Sheet
- Generate AI summaries for each new expense

## 🧠 Requirements
- n8n (local or cloud)
- Discord bot and webhook
- Google Sheets credentials
- Optional: Local LLM via Ollama (`phi3`, `llama3`, or similar)

## 🚀 Setup
1. Import the workflow into n8n (`Import from File`).
2. Update credentials for:
   - Discord (Webhook or REST API)
   - Google Sheets
   - LLM Node (Ollama or OpenAI)
3. Test by sending a message like:
Lunch ₱250 chicken rice

4. The bot replies with a concise AI summary and updates your sheet automatically.

## 📷 Preview
![Workflow Preview](https://github.com/Chigo042823/discord-google-sheets-expense-tracker-n8n/blob/main/src/preview1.png?raw=true)

## 🧾 License
MIT License
