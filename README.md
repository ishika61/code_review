# 🚀 AI Code Review Tool (Gemini API)

An AI-powered **Code Review Web Application** that analyzes source code and provides intelligent feedback using **Google Generative AI (Gemini API)**.  
The project is built with **React (Vite)** for the frontend and **Node.js + Express** for the backend.

---

## 🧠 Features

- 🤖 AI-based code review using **Google Generative AI (Gemini)**
- 📩 AI response handling using **POST requests**
- 🎨 Clean and responsive UI with modern styling
- ✨ **Syntax highlighting** using PrismJS
- 📝 **Markdown-rendered AI responses**
- 🌐 Axios-based API integration
- 🔐 CORS-enabled backend for secure communication

---

## 🎥 Demo & Flow

**Video Timeline**
- `00:00 – 01:05` → Introduction  
- User Flow & Preview  

**User Flow**
1. User enters source code in the editor
2. Code is sent to backend using POST request
3. Gemini API reviews the code
4. AI response is returned and rendered in Markdown format
5. Syntax-highlighted output is displayed on UI

---

## 🛠 Tech Stack

### Frontend
- React (Vite)
- Axios
- PrismJS
- Markdown Renderer
- CSS

### Backend
- Node.js
- Express.js
- Google Generative AI (Gemini API)
- CORS

---
2️⃣ Backend Setup
```
cd backend
npm install
npm start
```
Create a .env file:
```
GEMINI_API_KEY=your_api_key_here
```


3️⃣ Frontend Setup
```
cd frontend
npm install
npm run dev
```
