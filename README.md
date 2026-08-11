
# 🤖 Q&A Chatbot with Ollama

## Description

A simple **GenAI-based Q&A Chatbot** built using **Python, Streamlit, LangChain, and Ollama**. The application allows users to ask questions and receive responses from locally running LLMs through Ollama.

### Features

* Interactive Q&A chatbot using Streamlit
* Local LLM integration using Ollama
* LangChain prompt and output processing
* Temperature and maximum token configuration
* Support for multiple Ollama models
* LangSmith integration for application tracing and monitoring

### Tech Stack

* Python
* Streamlit
* LangChain
* Ollama
* LangSmith

## Setup

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Make sure Ollama is installed and pull a model, for example:

```bash
ollama pull llama3.2
```

Run the application:

```bash
streamlit run app.py
```

## Project Flow

```text
User Question
      ↓
Streamlit UI
      ↓
LangChain Prompt
      ↓
Ollama LLM
      ↓
Output Parser
      ↓
AI Response
```
