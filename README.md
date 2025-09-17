# SmartSDLS-AI 🚀 SmartSDLC – AI-Driven Software Development Lifecycle

SmartSDLC is an intelligent platform that leverages AI to automate and optimize every phase of the Software Development Lifecycle (SDLC).
Built with cutting-edge tools like FastAPI, Streamlit, LangChain, and IBM Watsonx AI, it aims to reduce manual effort, accelerate delivery, and enhance code quality.
Perfect for both developers and student project teams, SmartSDLC makes software engineering smarter and faster.


---

🌟 Key Highlights

📄 Scenario 1: Requirement Upload & Analysis

Upload raw requirement documents in PDF format.

Extract text with PyMuPDF (fitz).

AI classifies requirements into SDLC stages:

Requirements

Design

Development

Testing

Deployment


Convert into structured user stories and present them neatly in the frontend.



---

💻 Scenario 2: AI Code Generation

Input plain English requirements or user stories.

Generate ready-to-use production code powered by IBM Watsonx Granite-20B.

Output displayed in syntax-highlighted, copy-friendly format.



---

🐞 Scenario 3: Automated Bug Fixing

Upload buggy Python/JavaScript programs.

AI detects syntax and logical errors.

Provides corrected, optimized code instantly.



---

🛠️ Tech Stack

Backend: FastAPI + Uvicorn

Frontend: Streamlit

AI/LLM: IBM Watsonx AI + LangChain

PDF Parsing: PyMuPDF (fitz)

Version Control: Git + GitHub



---

📋 Setup Requirements

Ensure the following are installed:

Python 3.10

FastAPI

Streamlit

IBM Watsonx AI SDK

LangChain

Uvicorn

PyMuPDF (fitz)

Git & GitHub



---

🏗️ How It Works

1. Upload → PDF requirements extracted.


2. Classification → AI maps sentences to SDLC phases.


3. User Stories → Generate structured project stories.


4. Code Generator → AI produces working code.


5. Bug Fixer → Debug and improve existing code.


6. Docs → Auto-generate reports and documentation.




---

📂 Project Structure

SmartSDLC/
│
├── backend/          # FastAPI APIs
├── frontend/         # Streamlit dashboard
├── docs/             # Guides, reports, demos
├── samples/          # PDFs, test cases
├── requirements.txt  # Dependencies
└── README.md         # Overview


---

📜 License

Developed under the Naan Mudhalvan program for educational use.
Free to use, customize, and extend.
