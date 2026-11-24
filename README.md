# Real-Time Web Search AI Agent

An AI agent that answers questions using live web search. It is built with **LangChain** and **Google Gemini**, uses **Tavily** for real-time search, and runs in a **Streamlit** web app.

**🔗 Live demo: [realtimesearchaiagent.streamlit.app](https://realtimesearchaiagent.streamlit.app/)**

## What it does

Type a question and the agent decides which tool to use:

- **Web search (Tavily):** looks up current information that a language model alone doesn't know
- **System time tool:** returns the current date and time, so the agent can work out things like "how many days ago was X"

For example: *"When was the last SpaceX launch, and how many days ago was that?"* The agent searches for the launch date, checks today's date, and calculates the difference.

## Keywords

Generative AI · AI agents · LLM · ReAct agent · Tool calling · Real-time web search · Chatbot · LangChain · Google Gemini · Tavily · Streamlit · Python

## Tech Stack

- Python
- [LangChain](https://www.langchain.com/) (ReAct-style agent, `zero-shot-react-description`)
- [Google Gemini 2.0 Flash](https://ai.google.dev/) via `langchain-google-genai`
- [Tavily Search](https://tavily.com/) for web search
- [Streamlit](https://streamlit.io/) for the UI

## Project Structure

| File | Purpose |
| :--- | :--- |
| `app.py` | Streamlit UI, agent setup and tools |
| `requirements.txt` | Python dependencies |

## Author

**Amar Chaurasiya**, open to full-time roles and freelance work.

- Email: [amarchaurasiya124@gmail.com](mailto:amarchaurasiya124@gmail.com)
- LinkedIn: [amar-chaurasiya-163788262](https://www.linkedin.com/in/amar-chaurasiya-163788262)
- Portfolio: [amarchaurasiya.vercel.app](https://amarchaurasiya.vercel.app)
