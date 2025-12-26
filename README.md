# 🤖 AI-Agent

An AI chatbot backend built using **LangGraph**, **LangChain**, and **FastAPI**.  
Supports **Groq** and **OpenAI** models with optional web search using **Tavily**.

---

## 🚀 Features
- LangGraph ReAct AI agent
- Groq & OpenAI model support
- Optional web search (Tavily)
- FastAPI backend
- Secure `.env` based configuration

---

## 📁 Project Structure
AI-Agent/
├── agent.py
├── backend.py
├── frontend.py
├── Pipfile
└── README.md

yaml
Copy code

---

## ⚙️ Setup

```bash
git clone https://github.com/itskd2k69/AI-Agent.git
cd AI-Agent
pipenv install
pipenv shell
Create .env:

makefile
Copy code
GROQ_API_KEY=
OPENAI_API_KEY=
TAVILY_API_KEY=
▶️ Run
bash
Copy code
python backend.py
Open:

arduino
Copy code
http://127.0.0.1:9999/docs
📌 Example API Request
json
Copy code
{
  "model_name": "llama-3.3-70b-versatile",
  "model_provider": "Groq",
  "system_prompt": "Act as a smart and friendly AI chatbot",
  "messages": ["Tell me about crypto trends"],
  "allow_search": true
}
👨‍💻 Author
Kuldeep Amareliya
GitHub: https://github.com/itskd2k69

yaml
Copy code

---

✔ Short  
✔ Clean  
✔ Internship-ready  
✔ GitHub-friendly  
