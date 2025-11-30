# Local-LLM-Chat-System

Local AI chat system powered by a self-hosted LLM, with three different front-ends:
- Command Line Interface (CLI)
- Telegram Bot
- Local Web Interface

This repository documents the architecture and implementation of the project and provides all the source code inside the attached PDF guide.

---

## 🔍 Overview

The goal of this project is to run a Large Language Model (LLM) **locally**, without depending on external cloud APIs, and expose it through multiple interfaces:

- **CLI** – simple terminal chat client  
- **Telegram Bot** – remote access to the local model from any device  
- **Web UI** – local web page for chatting in the browser

This setup is useful for:
- privacy-friendly experiments with LLMs  
- building custom assistants on top of local models  
- integrating AI into automation workflows and security tools  

---

## 🧩 Architecture

High-level architecture:

- **Local LLM backend**  
  - Python scripts to load and run the model (e.g. Mistral)  
  - Model executed locally on the machine (no external API)

- **Interfaces**  
  - **CLI**: interactive terminal client  
  - **Telegram Bot**: bot that forwards messages to the local backend  
  - **Web Interface**: simple HTTP endpoint + HTML/JS front-end

- **Orchestration**  
  - Shared logic for prompt handling, context management and logging  
  - Possibility to plug the system into automation tools (e.g. n8n)

---

## 📄 Project Guide & Source Code

All details about:

- environment setup  
- model download and configuration  
- Python scripts  
- Telegram bot configuration  
- web interface  
- usage examples  

are available in the PDF included in this repository:

> **`Local-LLM-Chat-System-Guide.pdf`**

The PDF contains:
- step-by-step instructions  
- full source code  
- screenshots and explanation of each component

---

## 🛠 Technologies Used

- **Python**
- **Telegram Bot API**
- **Local LLM (e.g. Mistral)**
- **HTML / JavaScript (basic)**
- **Git & GitHub**

---

## 📌 Future Work

- Add direct source code files alongside the PDF  
- Provide Docker setup for easier deployment  
- Add authentication and access control for the web interface  
- Integrate with additional messaging platforms

---

## 👤 Author

Developed by **Rui Garripa Bastos**  
Cybersecurity & AI Enthusiast  
