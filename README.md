# Multi-Model Chatbot (Gemini + LLM Routing)

A multi-LLM chatbot integrating **Gemini + other LLM models**, designed to route user queries intelligently based on context.  
This project builds on a Next.js + TypeScript base and adds Gemini integration + routing logic.

> Built by **Shakshi Pal** during exploration of LLM + agentic AI workflows.


📸 Gemini Chat Demo

This project integrates Google Gemini models into a multi-LLM routing chatbot.
Below is a sample interaction using Gemini 2.5 Pro:
<img width="1919" height="963" alt="image" src="https://github.com/user-attachments/assets/9837e90e-2258-48d8-a012-bf8c47d92ff8" />


---

## 🚀 Features
- ✅ Multi-model query routing
- ✅ Gemini integration
- ✅ Modular provider design
- ✅ Context-aware responses
- ✅ Extensible architecture
- ✅ Web-based UI

---

## 🧠 Architecture Overview

User → Chat UI → Router → (Gemini / Other LLMs) → Response


Routing logic chooses model based on:
- Task type
- Domain
- Cost / capability

---

## 📂 Folder Structure
```
multi-model-chatbot-gemini/
│
├── src/
│ ├── app/ # UI pages
│ ├── libs/ # LLM clients + routing logic
│ ├── components/ # UI components
│ └── utils/ # helper methods
│
├── public/ # static assets
│
├── custom-mcp-server/ # MCP server setup
├── docker/ # docker config
├── tests/ # unit + integration tests
├── messages/ # config + prompts
│
├── package.json
├── README.md
├── next.config.js
├── .env.example



---

## 🛠️ Tech Stack

### ✅ Core
- Next.js
- TypeScript
- Gemini API
- Vercel AI SDK

### Optional
- LangChain
- MCP tools
- Docker

---

## 📦 Getting Started

### 1️⃣ Clone Repo
```bash
git clone https://github.com/Shakshi123pal/multi-model-chatbot-gemini
cd multi-model-chatbot-gemini

2️⃣ Install Dependencies
npm install

3️⃣ Add API Keys

Create .env from .env.example

GEMINI_API_KEY=xxxx

4️⃣ Run
npm run dev

````

✅ My Contributions


Integrated Gemini provider


Added multi-model routing logic


Updated UI flow for switching models


Added environment configuration for Gemini


Cleaned deployment setup


🔮 Future Improvements


Agent workflows


RAG + Vector DB (Qdrant / Pinecone)


Model selector UI


More model adapters


Voice input


✨ Author

Shakshi Pal
M.Sc. Data Science — IIIT Lucknow
GitHub: github.com/Shakshi123pal
