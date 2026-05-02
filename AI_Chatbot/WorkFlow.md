🤖 AI Chatbot Project Workflow
📌 Project Overview

This project is a Generative AI Chatbot built using Streamlit and Groq API.
It provides a conversational interface where users can interact with an AI assistant in real time.

🚀 Workflow of the Project
1️⃣ User Starts the Application
User runs the command:
streamlit run app.py
Streamlit launches a web-based chatbot UI in the browser.
2️⃣ Environment Setup
The application loads environment variables using .env
API key is securely retrieved:
GROQ_API_KEY
Connection is established with Groq API
3️⃣ Session Initialization
Streamlit initializes session state:
st.session_state.messages
A system prompt is added to define chatbot behavior:
Professional tone
Structured responses
Helpful assistant role
4️⃣ User Input Handling
User types a message in the chat input box
Message is stored in session memory as:
{"role": "user", "content": "message"}
5️⃣ API Request to LLM
The full conversation history is sent to Groq API
Model used:
llama-3.1-8b-instant
The AI processes:
User input
Chat history
System prompt
6️⃣ AI Response Generation
The model generates a response in real time
Response is returned as structured text
Stored in session memory as:
{"role": "assistant", "content": "response"}
7️⃣ Display Output in UI
Streamlit displays:
User message
AI response
Chat interface updates dynamically
8️⃣ Chat Memory Management
All conversations are stored in session state
Maintains context across messages
Enables continuous conversation flow
9️⃣ Reset Functionality
User can click Reset Chat
Session memory is cleared
Chat starts fresh with system prompt again
🧠 Architecture Flow
User Input
   ↓
Streamlit UI
   ↓
Session Memory (chat history)
   ↓
Groq API (LLM Processing)
   ↓
AI Response
   ↓
Streamlit UI Output
🔥 Key Features
💬 Real-time AI chat interface
🧠 Memory-based conversation
⚡ Fast LLM responses via Groq
🧑‍💼 Professional system prompt behavior
🔄 Reset chat functionality
🔐 Secure API key handling using .env
🎯 Use Cases
AI personal assistant
Customer support chatbot
Learning assistant
GenAI portfolio project