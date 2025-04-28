
# 🤖 Local AI Chatbot

A simple, private, and fully local chatbot built using **LangChain** and **Ollama** with the **Gemma 2B** model.  
The chatbot remembers conversation history during the session and responds intelligently.

---

## 📂 Features

- 💬 Interactive chat through the terminal.
- 🧠 Conversation memory (context-aware responses).
- 🚀 Powered by local LLM (no internet needed after setup).
- 🔒 Private and secure — runs 100% on your machine.

---

## 🛠️ Technologies Used

- Python
- LangChain
- Ollama
- Gemma 2B model

---

## 📥 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Install Python dependencies**

   ```bash
   pip install langchain langchain_ollama
   ```

3. **Install and run Ollama**

   - Install Ollama from [https://ollama.ai](https://ollama.ai)
   - Pull the **Gemma 2B** model:

     ```bash
     ollama pull gemma:2b
     ```

4. **Run the chatbot**

   ```bash
   python chatbot.py
   ```

---

## 🖥️ Usage

- After running the script, type your messages in the terminal.
- To end the conversation, simply type:

  ```bash
  exit
  ```

- The bot will remember the conversation history during the session.

---

## 🧩 Future Improvements

- ➕ Add Retrieval-Augmented Generation (RAG).
- 💾 Add long-term memory (saving chats across sessions).
- 🌐 Create a simple web UI (Streamlit or Gradio).
- 📚 Allow document uploads for retrieval-based conversations.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [LangChain](https://www.langchain.dev/)
- [Ollama](https://ollama.ai/)
- [Meta's Gemma Model](https://ai.meta.com/blog/meta-launches-gemma-open-source-models/)

---

# 🚀 Happy Chatting!
```
