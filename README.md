# 🤖 AI Code Reviewer

[![Python](https://img.shields.io/badge/Python-3.10+-blue)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.29-orange)](https://streamlit.io/)
[![License](https://img.shields.io/badge/License-MIT-green)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/status-active-success)](https://github.com/)

---

## 🚀 Project Overview

**AI Code Reviewer** is a modern web application that enables developers and students to automatically review Python code using:

- **Syntax validation**
- **Logical error detection**
- **PEP8 style formatting**
- **AI-powered code suggestions**

Built with **Python + Streamlit**, this tool is ideal for:
- Beginners learning Python  
- Developers wanting instant code feedback  
- Students preparing for coding interviews  
- Anyone who wants cleaner, error-free code

---

## 🧠 Key Features

### ✔️ Code Analysis & Error Detection
- Detects syntax errors using AST parsing  
- Identifies common logical mistakes  
- Provides line-by-line error reports

### 🧹 PEP8 Code Formatting
- Auto-formats Python code  
- Ensures clean, readable, and standard-compliant code  
- Improves consistency across projects

### 🤖 AI-Powered Suggestions
- Generates improvement suggestions using LLM  
- Suggests better logic, structure, and readability  
- Helps in learning best practices

### 🧩 Interactive Streamlit UI
- Clean UI with tabs for:
  - Code Input
  - Errors
  - Suggestions
  - Corrected Code

---

## 🏗️ Architecture & Workflow

```mermaid
flowchart LR
    A[User Input Code] --> B[Code Parser]
    B --> C[Error Detector]
    B --> D[Style Checker]
    C --> E[Error Report]
    D --> F[Corrected Code]
    A --> G[AI Suggester]
    G --> H[AI Suggestions]
    E --> I[Streamlit Output]
    F --> I
    H --> I
