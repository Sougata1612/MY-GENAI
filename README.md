# 🤖 MY-GENAI

MY-GENAI is a full-stack AI-powered web application built using the MERN stack. It provides users with an interactive AI chat interface that communicates with an AI model through a backend API.

---

## 🚀 Features

- 💬 AI-powered chatbot
- ⚡ Fast and responsive React frontend
- 🔒 Secure backend API
- 📜 Chat history (optional)
- 🎨 Modern UI with Vite + React
- 🌐 REST API integration
- 📱 Responsive design

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- JavaScript
- HTML5
- CSS3

### Backend
- Node.js
- Express.js
- OpenAI / Gemini API
- dotenv

---

## 📂 Project Structure

```
MY-GENAI
│
├── Backend
│   ├── src
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── Frontend
│   ├── src
│   ├── public
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Sougata1612/MY-GENAI.git
```

```bash
cd MY-GENAI
```

---

## Backend Setup

```bash
cd Backend
```

Install dependencies

```bash
npm install
```

Create a `.env` file

```env
PORT=5000

GEMINI_API_KEY=YOUR_API_KEY
```

Start the backend

```bash
npm start
```

or

```bash
node server.js
```

---

## Frontend Setup

Open another terminal

```bash
cd Frontend
```

Install dependencies

```bash
npm install
```

Start development server

```bash
npm run dev
```

The frontend will run on

```
http://localhost:5173
```

---

## 📡 API

Example endpoint

```
POST /api/chat
```

Request

```json
{
    "message": "Hello AI"
}
```

Response

```json
{
    "reply": "Hello! How can I help you today?"
}
```

---

## 📷 Screenshots

Add screenshots here after deployment.

```
Frontend Screenshot
```

```
Chat Interface
```

---

## 🌍 Environment Variables

Backend `.env`

```env
PORT=5000

GEMINI_API_KEY=YOUR_API_KEY
```

---

## 📦 Build

Frontend

```bash
npm run build
```

Backend

```bash
npm start
```

---

## 🤝 Contributing

1. Fork the repository

2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Create a Pull Request

---

## 👨‍💻 Author

**Sougata Manna**

- GitHub: https://github.com/Sougata1612

---

## ⭐ Show your support

If you like this project, please consider giving it a ⭐ on GitHub.
