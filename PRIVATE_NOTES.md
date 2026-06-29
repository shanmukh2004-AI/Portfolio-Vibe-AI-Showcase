# 🚀 Portfolio Vibe AI

> **An AI-Powered Resume-to-Portfolio Website Generator built with Python, Streamlit, and Google Gemini.**

Transform a resume into a complete, responsive portfolio website in minutes using Generative AI.

---

## 📌 Overview

Portfolio Vibe AI is an end-to-end Generative AI application that automatically creates a professional personal portfolio website from a user's resume and design instructions.

The application extracts information from PDF, DOCX, or TXT resumes, processes the content, uses Google's Gemini model to generate structured portfolio data, creates production-ready website source code (HTML, CSS, and JavaScript), launches a live preview, and packages the project into a downloadable ZIP file.

This project was built to demonstrate practical skills in:

* Generative AI
* Prompt Engineering
* LLM Application Development
* Resume Parsing
* AI Workflow Automation
* Python Backend Development
* Streamlit UI Development

---

# ✨ Features

* 📄 Resume Upload (PDF, DOCX, TXT)
* 🧹 Automatic Resume Text Cleaning
* 🤖 AI-Powered Portfolio Content Generation
* 🎨 AI-Based Portfolio Website Generation
* 🌐 Automatic Live Preview
* 📂 Source Code Viewer
* 📦 One-Click ZIP Download
* 💬 Chat-Based User Experience
* ⚡ End-to-End Automated Workflow

---

# 🏗️ System Architecture

```text
                 Resume
          (PDF / DOCX / TXT)
                     │
                     ▼
        Resume Text Extraction
                     │
                     ▼
          Resume Data Cleaning
                     │
                     ▼
          Google Gemini LLM
        (Portfolio Generation)
                     │
                     ▼
      Structured Portfolio JSON
                     │
                     ▼
      Portfolio Code Generation
                     │
                     ▼
     HTML + CSS + JavaScript Files
                     │
                     ▼
        Project Folder Creation
                     │
                     ▼
       Automatic Live Preview
                     │
                     ▼
            ZIP File Export
```

---

# 🔄 Workflow

### Step 1

Upload Resume

↓

### Step 2

Extract Resume Text

↓

### Step 3

Clean Extracted Data

↓

### Step 4

Generate Portfolio Content using Gemini

↓

### Step 5

Convert AI Response into Structured JSON

↓

### Step 6

Generate Complete Portfolio Source Code

↓

### Step 7

Create Project Structure

↓

### Step 8

Launch Local Preview Server

↓

### Step 9

Download Generated Portfolio ZIP

---

# 🖥️ User Interface

The application provides a modern Streamlit interface consisting of:

* Resume Upload
* AI Chat Input
* Live Portfolio Preview
* Source Code Viewer
* ZIP Download

---

# 📂 Project Structure

```text
Portfolio-Vibe-AI/

│
├── backend/
│   ├── call.py
│   ├── llm.py
│   ├── live.py
│   ├── main.py
│   ├── resume_extrector.py
│   └── __init__.py
│
├── frontend/
│   └── app.py
│
├── generated_portfolio/
│
├── uploads/
│
├── zip/
│
├── requirements.txt
│
└── README.md
```

---

# ⚙️ Tech Stack

## Programming Language

* Python

## AI Model

* Google Gemini

## Frontend

* Streamlit

## Backend

* Python

## Resume Processing

* pypdf
* python-docx

## API Communication

* google-genai

## Environment Variables

* python-dotenv

---

# 📦 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/portfolio-vibe-ai.git

cd portfolio-vibe-ai
```

Create a virtual environment

```bash
python -m venv venv
```

Activate environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Create a `.env` file inside the `backend` folder:

```env
GOOGLE_API_KEY=YOUR_GEMINI_API_KEY
```

Run the application

```bash
streamlit run frontend/app.py
```

---

# 📸 Screenshots

Add your screenshots here.

```
assets/

home.png

generation.png

preview.png

code.png
```

---

# 🧠 AI Pipeline

The application uses a multi-stage AI workflow:

1. Resume Parsing
2. Text Cleaning
3. Prompt Construction
4. Portfolio Content Generation
5. JSON Parsing
6. HTML/CSS/JS Generation
7. Project Folder Creation
8. Live Preview
9. ZIP Packaging

---

# 📁 Generated Output

The generated portfolio contains files similar to:

```text
candidate_portfolio/

│

├── index.html

│

├── assets/

│   ├── css/

│   │     style.css

│   │

│   ├── js/

│   │     script.js

│   │

│   └── data/

│         portfolio_data.json

│

└── README.md
```

---

# 🎯 Use Cases

* Resume to Portfolio Website
* Personal Branding
* Portfolio Creation
* Developer Portfolio Generation
* AI-Assisted Website Creation
* Learning Generative AI Pipelines

---

# 🚀 Future Improvements

Planned enhancements include:

* Multiple Portfolio Themes
* React Portfolio Generation
* Next.js Support
* Portfolio Editing
* Custom Domain Export
* Database Generation
* Backend API Generation
* One-Click Cloud Deployment
* Multi-Page Website Generation
* AI Design Assistant

---

# 💡 Key Highlights

* End-to-End AI Pipeline
* Production-Oriented Workflow
* Modular Python Architecture
* Streamlit-Based Interactive UI
* Google Gemini Integration
* Automated Website Generation
* Live Preview Support
* Downloadable Source Code

---

# 📄 License

This project is intended for educational, research, and portfolio demonstration purposes.

---

# 👨‍💻 Author

## DASARI SHANMUKHESWAR

**AI Engineer | NLP Engineer | Generative AI Developer**

Passionate about designing and building end-to-end AI applications powered by Large Language Models (LLMs), Natural Language Processing (NLP), and Python.

This project demonstrates my experience in building complete AI workflows—from document processing and prompt engineering to AI-generated web applications with automated live preview and source code generation.

### Areas of Interest

* Generative AI
* Large Language Models (LLMs)
* Natural Language Processing (NLP)
* AI Agents
* Prompt Engineering
* RAG (Retrieval-Augmented Generation)
* Python Backend Development
* AI Workflow Automation
* Streamlit Applications

### Connect With Me

📧 **Email:** [shanmukh8324@gmail.com](mailto:shanmukh8324@gmail.com)

💼 **Open to:** AI Engineer, NLP Engineer, Generative AI Engineer, LLM Engineer, Python AI Developer, and Machine Learning Engineer opportunities.

---

## ⭐ If you found this project helpful

If you found this project interesting or useful, please consider giving it a ⭐ on GitHub.

Feedback, suggestions, and contributions are always welcome.

Thank you for visiting this repository!


## ⭐ Support

If you found this project interesting, consider giving it a ⭐ on GitHub.

Feedback, suggestions, and contributions are always welcome.
