# Multi-Model Chatbot (Gemini + LLM Routing)

A lightweight chatbot application that integrates multiple LLM models
(e.g., Gemini + others) and intelligently routes queries to the most suitable
model based on user requirements.

> Built by **Shakshi Pal** as part of hands-on exploration in LLM + Agentic workflows.

---

## 🚀 Features

✅ Multi-model query routing  
✅ Context-aware responses  
✅ Gemini integration  
✅ Modular architecture for adding new models  
✅ Simple UI for interaction  

---

## 🧠 Architecture

User Query → Router → (Gemini / Other LLM) → Output

- The router selects the appropriate model based on:
  - user intent
  - domain
  - capability required

---

## 🛠️ Tech Stack

- Python
- Gemini API / Other LLM APIs
- LangChain (optional)
- FastAPI / Streamlit (optional)

---

## 📦 Getting Started

### 1️⃣ Clone Repo
```bash
git clone https://github.com/Shakshi123pal/multi-model-chatbot-gemini
cd multi-model-chatbot-gemini

pip install -r requirements.txt

3️⃣ Add API Key

Create .env

GEMINI_API_KEY=xxxx
OTHER_API_KEY=xxxx (optional)

python app.py

📂 Project Structure
├── app.py
├── utils/
│   ├── router.py
│   ├── gemini_client.py
│   └── other_model.py
└── README.md

🔥 Future Improvements

Agent workflows

Tools + RAG integration

Vector DB support

More model adapters

✨ Author

Shakshi Pal
M.Sc. Data Science — IIIT Lucknow
GitHub: github.com/Shakshi123pal
