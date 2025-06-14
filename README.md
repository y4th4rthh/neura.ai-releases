# Neura.ai

**Neura.ai** is a cutting-edge AI assistant powered by GPT with built-in voice interaction. Designed for seamless, real-time conversations, Neura combines the intelligence of large language models with the convenience of speech to deliver a smart, natural, and hands-free user experience.

Built with a modern tech stack—**React** for the frontend and **FastAPI (Python)** for the backend—Neura.ai is fast, modular, and scalable.

---

## 🔊 Key Features

- 🎤 **Voice Interaction**: Speak and listen to Neura just like a real assistant.
- 💡 **GPT Intelligence**: Backed by a powerful LLM for smart and contextual responses.
- ⚡ **Fast & Responsive**: Multiple plan tiers to suit your speed and feature requirements.
- 💻 **Modern Stack**: React + FastAPI for robust frontend/backend development.
- 🎨 **Chat Interface**: Clean, intuitive UI inspired by top voice assistants.
- 📰 **Real-Time News Suggestions**: Stay informed with the latest highlights from the past 6 hours.

---

## 🧠 Modal Plans

Neura comes in multiple variants to fit different user needs:

| Plan Name            | Speed            | Features                            | Availability              | Price         |
|----------------------|------------------|-------------------------------------|---------------------------|---------------|
| **neura.essence1.o** | 🐢 Ordinary       | Basic GPT + Voice Assist            | ✅ Available               | Free          |
| **neura.vista1.o**   | 🧠 Smart Web Mode | Specialized in web content summarization | ✅ Available              | Free          |
| **neura.swift1.o**   | 🚀 Faster         | Enhanced GPT, faster voice          | ✅ Available (Limited Use) | Free          |
| **neura.infinity1.o**| ⚡ Lightning Fast | Pro GPT, priority handling          | ❌ Dev only (Coming Soon)  | Paid (TBA)    |

---

## 🚀 Tech Stack

- **Frontend**: [React](https://reactjs.org/)
- **Backend**: [FastAPI](https://fastapi.tiangolo.com/)
- **Voice**: Web Speech API (Frontend) + TTS/STT services (Backend)
- **LLM**: GPT-based content generation
- **Deployment**: Docker (optional), hosted on cloud environments

---

## 🛠️ Installation & Setup

### Prerequisites

- Node.js
- Python 3.9+
- pip / poetry
- (Optional) Docker

### Clone the Repository

```bash
git clone https://github.com/y4th4rthh/neura.ai.git
cd neura.ai
```

### Frontend Setup

```bash
cd frontend
npm install
npm start
```

### Backend Setup

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

