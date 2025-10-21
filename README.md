AI-Powered Learning Platform

🚀 Overview

The AI-Powered Learning Mentor is an advanced educational platform built with Streamlit and LangChain, designed to guide learners across 70+ technical modules like Programming, Data Science, Cloud, and DevOps.
It features a secure login & registration system, AI mentorship, real code execution, progress tracking, and career preparation tools, making it a complete AI-driven learning companion.

🌟 Key Features

✅ 🔐 Secure Login & Registration — User accounts stored with SHA256 password encryption.
✅ 🤖 AI Mentor Assistance — Personalized responses using OpenRouter’s Mistral-7B AI model.
✅ 💻 Real Code Execution — Run Python, Java, and C++ programs directly in the app.
✅ 🎨 Multi-Theme UI — Choose from professional themes like Corporate Blue, Dark, Emerald, and more.
✅ 📚 Learning Modules — 70+ modules covering Programming, Data Science, Cloud, and Career topics.
✅ 📊 Progress Dashboard — Tracks total queries, session time, and completed modules.
✅ 🧩 Interactive Tools — Code Explainer, Syntax Checker, Resume Feedback, and Interview Prep.
✅ 📖 Bookmarks & Notes — Save AI responses and write personal learning notes.
✅ 📥 Report Export — Download session progress as a formatted text report.

🧩 Tech Stack
Component	Technology
Frontend/UI	Streamlit
Backend AI	OpenRouter API (Mistral 7B via LangChain)
Language	Python 3.x
Data Storage	JSON (for users and progress)
Authentication	SHA256 password hashing
Core Libraries	streamlit, langchain_openai, hashlib, json, subprocess, datetime

🗂️ Project Structure
AI-Powered-Learning-Mentor/
│
├── Login.py                # Main Streamlit app with login and mentor modules
├── users.json              # Stores registered users (auto-created)
├── requirements.txt        # Dependencies
└── README.md               # Documentation

📦 Example requirements.txt
streamlit
langchain_openai
langchain_core
requests
hashlib
json
subprocess
datetime

🧭 Usage Guide

Register or Login with a secure password.

Choose a learning module from the sidebar (e.g., Python, SQL, ML, AWS).

Ask questions or write code — AI will respond intelligently.

Run, save, or bookmark your learning sessions.

Export progress reports anytime.

🎨 Available Themes

Corporate Blue

Dark Professional

Emerald Green

Royal Purple

Sunset Orange
