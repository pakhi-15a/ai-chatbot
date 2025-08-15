# 💬 AI Chatbot

An interactive AI chatbot built with **FastAPI** (backend) and a modern **JavaScript frontend**, powered by the **Groq API** for intelligent conversations.  
Designed for fast responses, clean UI, and easy extensibility.

---

## 🚀 Features
- ⚡ **FastAPI** backend for high-performance API handling
- 🧠 **Groq API** for natural language processing
- 🎨 User-friendly frontend with chatbot UI
- 🔄 Real-time message updates
- 🛠 Easy to configure and extend

---

## 📂 Project Structure

- frontend/ # Chatbot UI (HTML, CSS, JS / React / Next.js)
- backend/ # FastAPI app with Groq integration
- requirements.txt
- README.md
- .gitignore

---

## 🛠 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/pakhi-15a/ai_chatbot.git
cd ai_chatbot
```

### 2️⃣ Create a Virtual Environment
- python -m venv .venv
- source .venv/bin/activate   # Linux/Mac
- .venv\Scripts\activate      # Windows

### 3️⃣ Install Dependencies
```
pip install -r requirements.txt
```

### 4️⃣ Set Environment Variables

Create a .env file in the root folder and add:
```angular2html
GROQ_API_KEY=your_api_key_here

```

### 5️⃣ Run the Backend
```
uvicorn app:app --reload
```


- Backend runs at: http://127.0.0.1:8000

### 🎨 Frontend Setup

If your frontend is built with Node.js:
```
cd frontend
npm install
npm start
```
- Frontend runs at: http://localhost:3000 (default)