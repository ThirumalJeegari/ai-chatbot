# 🤖 AI Chatbot (Streamlit + Groq API)

## 🚀 Overview

This project is an **AI-powered chatbot** that can understand user queries and generate intelligent responses using a Large Language Model (LLM).

It is built with **Python**, **Streamlit**, and the **Groq API**, providing a simple and interactive web interface for real-time conversations.

---

## 🎯 Features

* 💬 Interactive chatbot UI
* ⚡ Fast responses using Groq LLM
* 🧠 Context-aware conversations
* 🎨 Clean and minimal Streamlit interface
* 🔐 Secure API key handling using environment variables

---

## 🛠️ Tech Stack

* **Frontend:** Streamlit
* **Backend:** Python
* **LLM API:** Groq
* **Language Model:** llama3-8b-8192

---

## 📂 Project Structure

```
AI-Chatbot/
│
├── app.py              # Main Streamlit app
├── llm_helper.py       # Handles API calls
├── config.py (optional)# Centralized client setup
├── requirements.txt    # Dependencies
└── README.md           # Project documentation
```

---

## ⚙️ Installation

### 1. Clone the repository

```
git clone https://github.com/your-username/ai-chatbot.git
cd ai-chatbot
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

---

## 🔑 Setup API Key

### Windows (PowerShell)

```
$env:GROQ_API_KEY="your_api_key_here"
```

### Windows (CMD)

```
set GROQ_API_KEY=your_api_key_here
```

---

## ▶️ Run the Application

```
streamlit run app.py
```

---

## 💡 Usage

1. Enter your message in the input box
2. Click **Send**
3. Get AI-generated responses instantly

---

## 🧪 Example Prompt

```
Explain Python decorators in simple terms
```

---

## ⚠️ Common Errors & Fixes

### ❌ `client not defined`

✔ Ensure `client` is initialized in `llm_helper.py`

---

### ❌ API Key Error

✔ Make sure `GROQ_API_KEY` is set correctly

---

### ❌ Model Decommissioned

✔ Use a valid model:

```
llama3-8b-8192
```

---

## 📌 Future Improvements

* Chat history memory
* User authentication
* Multi-language support
* Voice input/output
* Deployment on cloud (Streamlit Cloud / AWS)

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

* Groq API
* Streamlit
* Open-source community

---

## 📧 Contact

**Thirumal Jeegari**
📍 India
📧 [your-email@example.com](mailto:your-email@example.com)

---

⭐ If you like this project, give it a star on GitHub!
