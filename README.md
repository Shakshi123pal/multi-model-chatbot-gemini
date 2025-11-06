# Multi-Model Chatbot (Gemini + LLM Routing)

A multi-LLM chatbot integrating **Gemini + other LLM models**, designed to route user queries intelligently based on context.  
This project builds on a Next.js + TypeScript base and adds Gemini integration + routing logic.

> Built by **Shakshi Pal** during exploration of LLM + agentic AI workflows.

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
└── LICENSE


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

🔥 Routing Logic
Located in:
src/libs

Routing decisions are based on:


User intent


Domain


Required capability


Model availability



🔮 Future Improvements


Agent workflows


RAG + Vector DB (Qdrant / Pinecone)


Model selector UI


More model adapters


Voice input



📸 Demo
(Add screenshots here)

✨ Author
Shakshi Pal
M.Sc. Data Science — IIIT Lucknow
GitHub: github.com/Shakshi123pal

---

# ✅ Why this is better
✔ Matches real files + stack  
✔ No copy-paste looking content  
✔ Shows YOUR contributions  
✔ Short + clean  
✔ Hiring-ready  

---

# ✅ IMPORTANT → What you must add
✅ A short section describing **Your Contribution**  
since repo is template-based

Example:


✅ My Contributions


Integrated Gemini provider


Added multi-model routing logic


Updated UI flow for switching models


Added environment configuration for Gemini


Cleaned deployment setup



This is **crucial** —  
so reviewer knows what YOU built vs what came from original template.

---

# ✅ Next step
If you want,  
I can also write a **tiny banner in README**:

> "This project is adapted from an open-source template; extended with Gemini routing + custom logic."

This makes everything transparent + honest.  
Good for interviews ✅

---

If you want,  
I can also prepare a **short RESUME bullet** for this project.


✨ Author

Shakshi Pal
M.Sc. Data Science — IIIT Lucknow
GitHub: github.com/Shakshi123pal
