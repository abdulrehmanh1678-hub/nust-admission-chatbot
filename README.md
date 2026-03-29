# nust-admission-chatbot
NUST Admission Helper Chatbot - Offline FAQ Bot using n8n and Ollama
# NUST Admission Helper Chatbot

An offline FAQ chatbot for NUST admissions built with n8n and Ollama.

## Features
- 73 NUST FAQs
- Works completely offline
- No internet needed
- Fast keyword matching

## Setup

### Requirements
- Docker Desktop
- n8n running in Docker
- Ollama (optional)

### Installation

1. Clone this repo
```bash
git clone https://github.com/YOUR_USERNAME/nust-admission-chatbot.git
cd nust-admission-chatbot
```

2. Import workflow.json into n8n

3. Test:
```bash
curl -X POST http://localhost:5678/webhook-test/chatbot -H "Content-Type: application/json" -d '{"query":"quota"}'
```

## Usage

Ask questions about NUST admissions:
- "Are there quota seats?"
- "What is the fee?"
- "Can I apply?"

## Technologies
- n8n (workflow automation)
- Docker (containerization)
- Ollama (optional AI)
```

**FAQ.json** (copy your 73 FAQs JSON)

**.gitignore**
```
node_modules/
.env
.DS_Store
*.log
