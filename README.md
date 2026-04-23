# 🧠📄 Multi-format File-based QnA System

> Can a machine truly understand your documents and answer questions from them?

This project is an AI-powered document intelligence system that allows users to upload multiple file formats and ask natural language questions to get context-aware answers instantly.

Instead of manually reading long documents, the system extracts knowledge from your files.

---

## 🚀 Why this project?

Reading multiple documents is time-consuming and inefficient.

- PDFs are long and dense  
- PPTs contain scattered information  
- Images may contain hidden text  
- Word files are unstructured  

This raises an important question:

> Instead of reading everything manually, what if we could simply ask questions and get answers directly from our documents?

That idea forms the foundation of this project — turning static files into an interactive, query-driven knowledge system.

---

## 🧪 Features

- 📁 Upload multiple file formats (PDF, DOCX, PPTX, TXT, Images)
- 🧠 Extract text using parsing + OCR (EasyOCR)
- 💬 Ask natural language questions
- 🤖 AI-powered answer generation using FLAN-T5
- 📌 Select specific file for targeted Q&A
- 📝 Stores Q&A history per file
- 📥 Download complete Q&A session
- 🌐 Simple Flask-based web interface

---

## 💬 Q&A Output

![Q&A Result](QnA_Result.png)

The system extracts relevant context from the selected document and generates accurate, human-like answers using AI.

## 🧠 AI Model Used

### 🔹 FLAN-T5 (Google)

- Type: Text-to-Text Transformer
- Purpose: Generates detailed and natural answers
- Strength: Better reasoning and explanation than extractive QA models

Instead of copying sentences, it generates **human-like explanations based on context**.

---

## 🛠️ Tech Stack

- Python 🐍
- Flask 🌐
- HuggingFace Transformers 🤖
- FLAN-T5 Model 🧠
- EasyOCR 👁️
- PyPDF2 📄
- python-docx 📄
- python-pptx 📊
- HTML / CSS 🎨

---

## 🌍 Applications

- 🎓 Smart study assistant for students
- 🏢 Document intelligence system for companies
- 📚 Research paper understanding tool
- 🧾 Legal document analysis assistant

---

## 🔮 Future Improvements

- 🔍 Semantic search using vector databases (FAISS / ChromaDB)
- 🧠 Upgrade to LLaMA / Mistral models
- 📊 Highlight answer source in document
- 🎙️ Voice-based Q&A system

---

## 👩‍💻 Author

**Manasi Masali**

📧 Email: masalimanasi@gmail.com
💼 LinkedIn: www.linkedin.com/in/manasi-masali  

---

## 🌟 Final Note

This project demonstrates how AI can transform static documents into interactive knowledge systems — making information more accessible, searchable, and intelligent.
