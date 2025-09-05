# Ask-My-PDF

Ask-My-PDF is an AI-powered application that lets you upload any PDF and then **ask natural-language questions** about its contents.  
It combines a **Streamlit frontend** with a **FastAPI backend**, uses **LangChain + ChromaDB + SQLite** for document processing and semantic search, and leverages the **OpenAI API** for intelligent question answering.

---

##  Features
-  Upload any PDF document.
-  Ask questions in plain English about the content.
-  Powered by **LangChain** for document chunking, embeddings, and retrieval.
-  ChromaDB + SQLite for efficient vector search and metadata storage.
-  FastAPI backend for API requests.
-  Streamlit frontend for an interactive UI.
-  Secure environment configuration via `.env`.
-  MIT Licensed (free to use and modify).

---

##  Tech Stack
- [Streamlit](https://streamlit.io/) – Frontend
- [FastAPI](https://fastapi.tiangolo.com/) – Backend API
- [LangChain](https://www.langchain.com/) – LLM orchestration
- [ChromaDB](https://www.trychroma.com/) – Vector database
- [SQLite](https://www.sqlite.org/) – Metadata storage
- [OpenAI API](https://platform.openai.com/) – LLM for answering questions
- [Python 3.10+](https://www.python.org/)

---

### 1. Clone the Repository
```bash
git clone https://github.com/Reyad02/Ask-My-PDF.git
cd Ask-My-PDF
```

### 2. Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Backend (FastAPI)
```bash
cd Backend
uvicorn main:app --reload
```

### 5. Run the Frontend (Streamlit)
```bash
cd Frontend
streamlit run app.py
```
## Demo
![image_alt](https://github.com/Reyad02/Ask-My-PDF/blob/3b2a1a0fc19e8c0567949d0ce636260cbb642aed/Demo.jpg)
