# Building LLM Applications With Prompt Engineering

![NVIDIA Header](https://github.com/Swanjith/Building-LLM-Applications-With-Prompt-Engineering/blob/main/nvidia_header.png?raw=true)

**Course:** Building LLM Applications with Prompt Engineering

---

## Overview

This project demonstrates concepts and practical applications covered in the NVIDIA DLI course on Prompt Engineering and LLM-based Application Development. It walks through designing effective prompts, integrating retrieval mechanisms, using memory, and deploying real-world LLM applications with tools and agents.

---

## Learning Objectives

- Understand the mechanics of prompt engineering
- Design zero-shot, few-shot, and chain-of-thought prompts
- Use prompt templates to guide and format LLM responses
- Build Retrieval-Augmented Generation (RAG) applications using FAISS or Chroma
- Apply LangChain memory for contextual conversations
- Incorporate tool usage and agents into LLM workflows
- Deploy LLM-powered apps using NVIDIA Triton Inference Server

---

## Tech Stack

| Layer            | Tools / Frameworks                               |
|------------------|--------------------------------------------------|
| LLM              | OpenAI GPT, Mistral, Claude                      |
| Prompting        | LangChain PromptTemplate, Few-shot Prompts       |
| Vector DB        | FAISS, ChromaDB                                  |
| Retrieval        | LangChain Retriever + Custom Splitters           |
| Agents & Tools   | LangChain Agents, Calculator, Web Search Tools   |
| Memory           | ConversationBufferMemory, VectorStoreMemory      |
| UI               | Streamlit, Gradio                                |
| Deployment       | NVIDIA Triton, Docker, NGC                       |

---
 ```bash
# 1. Create a Python environment
conda create -n llm-course python=3.10
conda activate llm-course

# 2. Install dependencies
pip install langchain streamlit openai faiss-cpu chromadb

# 3. Run the app
streamlit run ui/chat_app.py
```
---
