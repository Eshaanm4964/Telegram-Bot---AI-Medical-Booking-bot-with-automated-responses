**🤖 Telegram Bot Automation using n8n**
**Overview**

This project implements a Telegram bot integrated with n8n that receives user messages, processes them through an automated workflow, and stores relevant data in Google Sheets for persistence and tracking.

**Features**

Real-time message handling via Telegram Trigger

Automated response generation using n8n logic

User data logging in Google Sheets

Event-driven workflow execution

**Tech Stack**

n8n

Telegram Bot API

Google Sheets

Workflow Summary
Telegram Trigger
       ↓
Process User Message
       ↓
Save Data to Google Sheets
       ↓
Send Reply via Telegram

Setup Steps

Create a Telegram bot using BotFather

Configure Telegram API credentials in n8n

Add Telegram Trigger node to receive messages

Append user data using Google Sheets – Append Row

Send responses via Telegram Send Message

Activate the workflow

**How to Test ?**

Open the Telegram bot

Send a message

**Verify:**

Workflow execution in n8n

Message saved in Google Sheets

Response received in Telegram

**Conclusion**

This project demonstrates a practical Telegram-based automation system using n8n, combining conversational interaction with persistent data storage in Google Sheets.
