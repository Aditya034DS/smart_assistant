# 📚 Smart Research Assistant (No API Needed)

An AI-powered assistant that can read, understand, and reason through uploaded research documents (PDFs). Unlike basic keyword searches or simple summarizers, this app supports intelligent summarization and question-answering using Hugging Face models — all without needing a separate backend API!

---

## 🚀 Features

- 🔍 **Automatic Summarization** of uploaded PDFs
- 🤖 **Question Answering** from document content
- 🧠 **Challenge Mode** (for future improvements)
- 🛠️ No backend API required — works entirely via `streamlit`

---

## 🧰 Tech Stack

- `Python`
- `Streamlit`
- `transformers` (Hugging Face)
- `PyMuPDF` (for PDF reading)
- `torch`

---

## 📦 Setup Instructions (Run Locally)

1. **Clone this repo**:

```bash
git clone https://github.com/YOUR_USERNAME/smart_assistant.git
cd smart_assistant

pip install -r requirements.txt


streamlit run app.py

📁 How to Use
Upload a PDF file (max 200MB)

Choose a mode:

Ask Anything: Type a question based on the document

Challenge Me: (For future use)

See intelligent answers and confidence scores
