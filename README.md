🤖 Local AI Chatbot
A simple, private, and fully local chatbot built using LangChain and Ollama with the Gemma 2B model.
The chatbot remembers conversation history during the session and responds intelligently.

📂 Features
💬 Interactive chat through the terminal.

🧠 Conversation memory (context-aware responses).

🚀 Powered by local LLM (no internet needed after setup).

🔒 Private and secure — runs 100% on your machine.

🛠️ Technologies Used
Python

LangChain

Ollama

Gemma 2B model

📥 Installation
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
Install Python dependencies

bash
Copy
Edit
pip install langchain langchain_ollama
Install and run Ollama

Install Ollama from https://ollama.ai

Pull the Gemma 2B model:

bash
Copy
Edit
ollama pull gemma:2b
Run the chatbot

bash
Copy
Edit
python chatbot.py
🖥️ Usage
After running the script, type your messages in the terminal.

To end the conversation, simply type:

bash
Copy
Edit
exit
The bot will remember the conversation history during the session.

🧩 Future Improvements
➕ Add Retrieval-Augmented Generation (RAG).

💾 Add long-term memory (saving chats across sessions).

🌐 Create a simple web UI (Streamlit or Gradio).

📚 Allow document uploads for retrieval-based conversations.

📄 License
This project is licensed under the MIT License.

🙌 Acknowledgements
LangChain

Ollama

Meta's Gemma Model

🚀 Happy Chatting!
