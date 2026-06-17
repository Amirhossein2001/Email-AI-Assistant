Email Automation Agent built with n8n + LLM

📌 Overview

This project is an automated email system built using n8n and integrated with LLM-based intelligence.

It allows users to trigger email actions using simple inputs and can be extended into a fully autonomous AI email assistant.

🚀 What it does
Receives structured email instructions (recipient, subject, message)
Processes data through an automated n8n workflow
Sends emails automatically via SMTP / email provider
Optionally uses an LLM to generate or improve email content
Fully workflow-based system (no traditional backend required)
🧠 Core Idea

Instead of manually writing and sending emails, the system automates the entire process:

User Input → n8n Workflow → (Optional LLM Processing) → Email Sent

🛠️ Tech Stack
n8n – Workflow automation engine
LLM (Ollama / OpenAI compatible) – Text generation and understanding
SMTP / Email Service – Email delivery
Webhooks – Trigger-based input handling
emai-workflow.png
⚙️ How it works
A request is sent to the n8n webhook
The workflow extracts email details
(Optional) LLM generates or improves the email content
The final email is sent automatically to the recipient
📌 Status

This project is currently running locally and was built for learning and demonstration purposes.
It works in a development environment and can be deployed if needed.

🚀 Future Improvements
Incoming email (Inbox) processing
AI-generated automatic replies
Full AI Email Assistant (send + read + respond)
Multi-provider email support
Improved context handling with LLM memory
🎯 Goal

This project demonstrates practical experience in:

Workflow automation using n8n
AI integration in real-world systems
Designing automation pipelines
Using LLMs for practical productivity tools
