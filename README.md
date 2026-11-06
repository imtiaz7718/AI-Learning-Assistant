# 🌈 AI Study Guide - LangGraph & Streamlit

An interactive AI-powered study guide application built with **Streamlit**, orchestrated using **LangGraph**, and accelerated by ultra-fast inference via the **Groq API**.

---

## 📌 Project Overview

This application helps learners study complex topics by breaking them down into structured study guides, summaries, and interactive quizzes. The system leverages **LangGraph** to model multi-step agentic workflows and chains, delivering low-latency responses powered by Groq-hosted LLMs.

---

## 🛠️ Tech Stack

- **Frontend & UI:** [Streamlit](https://streamlit.io/)
- **Agent Orchestration:** [LangGraph](https://github.com/langchain-ai/langgraph) / [LangChain](https://www.langchain.com/)
- **Inference Engine:** [Groq Cloud API](https://groq.com/)
- **Language:** Python 3.10+

---

## 📂 Project Structure

```text
AI_Workshop/
├── myenv/               # Virtual environment (ignored by git)
├── .env                 # Environment variables (API keys)
├── main.py              # Main Streamlit application and workflow entrypoint
└── requirements.txt     # Python dependencies
