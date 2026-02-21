# 🤖 AI Chatbot (Groq + Streamlit)

An interactive AI chatbot web application built with **Streamlit** and powered by **Groq LLMs**. The app provides real-time conversational responses with support for multiple large language models through a clean and user-friendly interface.

🌐 **Live Demo:** https://chat-project-gold.vercel.app/
📦 **Repository:** https://github.com/sonukumar864/Chatbot

---

## 🚀 Features

* 💬 Real-time conversational chat UI
* 🧠 Multiple LLM support (Llama-3, Mixtral, Gemma)
* ⚡ Fast inference using Groq API
* 🗂️ Session-based chat history
* 🎛️ Sidebar model selection
* 🔐 Secure API key management using `.env`
* 📱 Clean and responsive Streamlit interface

---

## 🛠️ Tech Stack

**Frontend/UI**

* Streamlit
* Python

**AI / Backend**

* Groq API
* Large Language Models:

  * Llama-3-8B
  * Llama-3-70B
  * Mixtral-8x7B
  * Gemma-7B

**Environment Management**

* python-dotenv

---

## 📂 Project Structure

```
Chatbot/
├── app.py
├── .env
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/sonukumar864/Chatbot.git
cd Chatbot
```

### 2️⃣ Create virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔐 Environment Variables

Create a `.env` file in the root directory:

```
GROQ_API_KEY=your_groq_api_key_here
```

---

## ▶️ Run the App

```bash
streamlit run app.py
```

App will run on:

```
http://localhost:8501
```

---

## 🧠 Supported Models

| Model        | Description                     |
| ------------ | ------------------------------- |
| Llama-3-8B   | Fast and lightweight            |
| Llama-3-70B  | More powerful reasoning         |
| Mixtral-8x7B | Strong mixture-of-experts model |
| Gemma-7B     | Efficient instruction model     |

---

## 🎯 Future Improvements

* 🔄 Streaming responses
* 💾 Persistent chat history (database)
* 🔐 User authentication
* 🌙 Dark mode toggle
* 📊 Usage analytics
* 🧩 Prompt templates

---

## 👨‍💻 Author

**Sonu Kumar**

* GitHub: https://github.com/sonukumar864
* LinkedIn: https://www.linkedin.com/in/sonu-kumar-5b8722282

---

## ⭐ Support

If you found this project helpful, please give it a ⭐ on GitHub!
