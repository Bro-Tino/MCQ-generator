# 🧠 MCQ Generator from PDFs

Generate intelligent multiple-choice questions (MCQs) from PDF files using LLMs, FAISS vector search, and Streamlit!

## 🚀 Demo

Upload a PDF and get a set of MCQs instantly, powered by embeddings and language models.

## 📦 Features

- 📄 Upload any educational PDF
- 🤖 Extract context using `LangChain` and embeddings
- 🧠 FAISS vector store for similarity search
- ✍️ Auto-generate MCQs with accurate distractors
- 💻 Interactive UI with `Streamlit`


---

## 🛠️ Installation
# Clone the repository
git clone https://github.com/Bro-Tino/MCQ-generator.git
cd MCQ-generator

# Create and activate virtual environment
python -m venv venv
venv\Scripts\activate     # On Windows

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run MCQ-generator.py

