# 🧠 Summarize YouTube or Web Content using LangChain & Groq

## 📌 Project Overview

This Streamlit app allows users to input a **YouTube or website URL** and get a concise summary of its content using **LangChain**, **Groq's Gemma-7B model**, and advanced text parsing tools.

## 🚀 Features

- 📺 Accepts YouTube video URLs or standard web URLs
- 📄 Loads and extracts text from video transcripts or HTML pages
- 🧠 Summarizes long-form content into ~300 words using Groq’s Gemma-7B LLM
- 🔒 Secured with user-provided Groq API key via Streamlit sidebar
- ⚡ Powered by LangChain's `load_summarize_chain` and PromptTemplate modules

## 🧰 Tech Stack

- Python 3.8+
- Streamlit
- LangChain
- Groq API (Gemma-7B-It)
- YoutubeLoader / UnstructuredURLLoader (LangChain Community)

## ▶️ How to Run Locally

```bash
git clone https://github.com/rohitsahayy/Web-Content-Summarizer-using-LangChain.git
cd yt-web-summarizer
pip install -r requirements.txt
streamlit run app.py
```

## 🔐 Input Required

- **Groq API Key** – Can be generated from your [Groq account](https://console.groq.com/)
- **URL Input** – YouTube or any website containing summarizable text

## 📦 Requirements

```bash
streamlit
langchain
langchain-groq
langchain-community
validators
```

## 👤 Author

**Rohit Sahay**  
GitHub: [@rohitsahayy](https://github.com/rohitsahayy)
