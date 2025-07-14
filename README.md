# Inventory-Ai-Agent
# 🛒 Grocery Inventory Management 📊

Welcome to the **Grocery Inventory Management** system — a lightweight, automated project built using **n8n** and **Google Sheets** to manage stock efficiently! 🚀

---

## 📌 Project Overview

This project helps streamline the tracking and updating of inventory in a grocery warehouse using the power of automation. It integrates:

- 🧠 **AI-powered Chat Interface** (via n8n)
- 📄 **Google Sheets** for data storage and updates
- 🔁 Real-time inventory updating and retrieval
- 💬 Responds to user queries and automates stock adjustments

---

## 🔧 Features

✅ Google Sheets integration to store item name and quantity  
✅ Smart AI Agent to process chat-based inventory commands  
✅ Real-time updates using n8n workflows  
✅ Scalable for small-to-medium businesses  

---

## ⚙️ Tech Stack

| Tool | Purpose |
|------|---------|
| `n8n` 🧩 | Automation workflows and node-based logic |
| `LangChain` 💬 | Handles the AI chat logic |
| `Google Sheets` 📈 | Acts as the inventory database |
| `OpenRouter` 🤖 | For language model communication |

---

## 🚀 How It Works

1. 🧑‍💻 A user sends a chat message (e.g., “Update milk quantity to 20”).
2. 🤖 The message is captured by n8n's **ChatTrigger**.
3. 🧠 The **AI Agent** interprets the command.
4. 📤 The appropriate row in Google Sheets is updated using the **AppendOrUpdate** node.

---

## 📊 Example Google Sheet

👉 [Click here to view the example inventory sheet](https://docs.google.com/spreadsheets/d/1nQ6v2_n0AAx54jG8layt3BFz2u4hKlu53ZC6SLVHeno/edit#gid=1964897189)



Link - https://shubh7777.app.n8n.cloud/webhook/377f8e0e-ee37-49d4-a628-1385e7aceedc/chat

