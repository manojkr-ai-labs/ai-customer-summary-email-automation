# AI Customer Summary & Email Automation

AI-powered business workflow that automatically processes
customer information from Google Sheets, generates an
LLM-powered summary, and sends the result through Gmail.

## 🎯 Problem

Customer information stored in spreadsheets often requires
manual review and communication.

## 💡 Solution

This workflow automates the process using n8n and an LLM.

Google Sheets
→ n8n
→ OpenAI
→ Customer Summary
→ Gmail

## 🏗️ Architecture

![Architecture](docs/architecture.png)

## 🔄 Workflow

![n8n Workflow](docs/workflow.png)

## 🤖 AI Capabilities

- LLM integration
- Prompt engineering
- Customer information summarization
- Structured data processing

## ⚙️ Automation

- Event-driven workflow
- Google Sheets integration
- Gmail integration
- API orchestration
- Automated notification

## 🧰 Tech Stack

- n8n
- OpenAI API
- Google Sheets
- Gmail
- JSON
- REST APIs

## 📂 Repository Structure

workflow/   → n8n workflow JSON
docs/       → Architecture and screenshots
prompts/    → LLM prompts
examples/   → Sample input/output

## 🔐 Security

No production credentials or API keys are included.

Use environment variables or n8n credentials for secrets.

## 🚀 Production Improvements

- Error handling
- Retry mechanism
- Input validation
- Structured LLM output
- Logging
- Monitoring
- Rate-limit handling
- Human approval
- LLM evaluation

## 🧠 Skills Demonstrated

- Generative AI
- LLM Integration
- Prompt Engineering
- n8n
- Workflow Automation
- API Integration
- Data Processing
- Business Process Automation
