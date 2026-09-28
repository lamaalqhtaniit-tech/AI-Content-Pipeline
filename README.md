# SAGE – AI Content Pipeline

SAGE is an agentic AI application that automates the creation of educational content from a given topic.

It uses an AI workflow to research and organize information, generate structured learning content, create assessments, evaluate the generated content, and produce ready-to-use educational files.

## 🚀 Live Demo

[Try SAGE](https://ai-content-pipeline-esc7lxxjxmoddnnqc4qvxn.streamlit.app/)

## ✨ Key Features

- Generate structured educational content from a topic
- AI-powered research and RAG workflow
- Generate presentations automatically
- Generate quizzes and assessments
- Generate answer keys
- Evaluate generated content
- Optional AI-based revision
- Export content as PPTX and DOCX
- Generate a ZIP package containing the final outputs
- Support for Arabic and English content
- Support for RTL Arabic presentation formatting

## 🧠 Agentic AI Workflow

SAGE follows a multi-step AI workflow:

**User Input → Planning → Research / RAG → Content Generation → Assessment Generation → Evaluation → Optional Revision → Export**

Each stage contributes to producing a complete and structured educational package.

## 🔎 RAG & Research

The system can retrieve relevant information during the content creation process and use it as context for the language model.

This helps the generated educational content stay more structured and grounded in the retrieved information.

## 📚 Educational Outputs

SAGE can generate:

- Lesson content
- Presentation slides
- Multiple-choice questions
- True/False questions
- Teacher answer keys
- Educational documents

The final materials can be exported as:

- PowerPoint (`.pptx`)
- Word document (`.docx`)
- ZIP package (`.zip`)

## 🛠️ Tech Stack

- Python
- Streamlit
- OpenAI API
- RAG
- LLMs
- Pydantic
- python-pptx
- python-docx

## 🏗️ Project Structure

- `app4.py` — Main Streamlit application
- `requirements.txt` — Python dependencies
- `.gitignore` — Protects secret files from being uploaded
- `README.md` — Project documentation

## 🎯 Project Goal

The goal of SAGE is to reduce the manual effort required to prepare educational materials by combining generative AI, retrieval, evaluation, and automated document generation into one workflow.

## 🔐 Security

API credentials are stored using Streamlit Secrets and are excluded from the GitHub repository using `.gitignore`.

---

## 👩🏻‍💻 Project

Developed as an Agentic AI project using Python, LLMs, RAG, and Streamlit.


API credentials are stored using Streamlit Secrets and are excluded from the GitHub repository using .gitignore.

👩🏻‍💻 Project

Developed as an Agentic AI project using Python, LLMs, RAG, and Streamlit.
