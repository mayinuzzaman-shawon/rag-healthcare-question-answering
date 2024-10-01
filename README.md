# Healthcare Question Answering System using Retrieval Augmented Generation (RAG) Technique & Leveraging LLM

## Overview

This project involves building a Python application that implements a **Healthcare Question Answering System** using **Langchain** and leveraged **Retrieval-Augmented Generation (RAG)** technique of Large Language Model (LLM). The system loads a research paper on latest findings of Alzheimer's disease as its external knowledge base, retrieves relevant sections from the document, and answers user questions leveraging OpenAI LLM (gpt-3.5-turbo). The application provides an intuitive GUI built with Tkinter for ease of use.

## Features

- **Tkinter-based GUI**: A graphical interface where users can input question/prompt and receive answers.
- **Retrieval-Augmented Generation (RAG)**: Uses context retrieval from the external knowledge base and answers questions by leveraging GPT-based large language model (gpt-3.5-turbo).

## Requirements

To run this project, you'll need the following Python packages:

- `langchain`
- `langchain_community`
- `tkinter`
- `scrolledtext`
- `openai`
- `faiss-cpu`
- `transformers`

You can install these dependencies using:

```bash
pip install langchain langchain_community tkinter faiss-cpu transformers openai

## How The RAG-based Application Works

- **Document Loading**: The system can load research paper(s) in PDF format using `PyPDFLoader`.
- **Question-Answering**: The system retrieves relevant document sections and generates answers with the OpenAI GPT model (gpt-3.5-turbo).
- **Graphical User Interface**: The Tkinter GUI provides an interactive way for users to ask questions and get relevant answers retrieved from the latest research findings from the external knowledge base.

