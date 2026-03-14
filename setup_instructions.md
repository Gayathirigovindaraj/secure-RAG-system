# Secure RAG System -- Setup Instructions

This guide explains how to set up and run the Secure Retrieval-Augmented
Generation (Secure RAG) project locally.

## 1. Clone the Repository

git clone https://github.com/your-username/secure-rag-system.git cd
secure-rag-system

## 2. Create Virtual Environment (Recommended)

### Windows

python -m venv venv venv`\Scripts`{=tex}`\activate`{=tex}

### Linux / Mac

python3 -m venv venv source venv/bin/activate

## 3. Install Dependencies

pip install -r requirements.txt

## 4. Run the Project

Open and run:

SECURE RAG SYSTEM PROJECT CODE.ipynb

Project steps:

1.  Load domain documents
2.  Preprocess and chunk text
3.  Generate embeddings
4.  Store embeddings in FAISS vector database
5.  Apply RBAC access control
6.  Retrieve relevant documents
7.  Generate responses
8.  Verify outputs and log activity

## 5. Project Structure

Secure-RAG-System/ │ ├── src/ ├── docs/ ├── SECURE RAG SYSTEM PROJECT
CODE.ipynb ├── requirements.txt ├── architecture.png ├──
setup_instructions.md ├── demo_video_link.txt └── README.md

## 6. System Requirements

Python 3.8+ Recommended RAM: 8GB

## 7. Author

Gayathri G\
Artificial Intelligence and Data Science\
Alliance University
