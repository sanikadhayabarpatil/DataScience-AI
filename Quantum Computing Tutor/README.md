
# Quantum Computing Tutor

## Project Overview
Quantum Computing Tutor is an AI-powered **learning assistant** designed to help users explore **quantum computing** concepts. The project features a **FastAPI backend** for processing queries, summarizing documents, and retrieving research papers, while the **Streamlit frontend** provides an interactive user interface.

## Features
- **Question-Answering System**: Ask quantum computing questions and receive AI-powered responses.
- **Document Summarization**: Upload or select a quantum computing-related PDF and generate a structured summary.
- **Research Paper Retrieval**: Fetch relevant papers from **arXiv** and other sources.
- **Parallel Processing**: Uses **Pinecone**, **OpenAI Embeddings**, and **AWS S3** for optimized search and storage.

## Installation
Ensure you have the required dependencies installed before running the application:

```bash
pip install -r requirements.txt
```

## How to Run
### Backend (FastAPI)
1. Navigate to the backend folder:
    ```bash
    cd backend
    ```
2. Start the FastAPI server:
    ```bash
    uvicorn main:app --host 0.0.0.0 --port 8000
    ```
3. The API will be available at `http://127.0.0.1:8000`.

### Frontend (Streamlit)
1. Navigate to the frontend folder:
    ```bash
    cd frontend
    ```
2. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```
3. The app will be accessible at `http://localhost:8501`.

## File Structure
- `main.py` – FastAPI backend for handling requests and document processing.
- `app.py` – Streamlit frontend for user interaction.
- `scraper.py` – Web scraper for retrieving quantum computing-related articles.
- `requirements.txt` – List of dependencies required for the project.

## Technologies Used
- **Backend**: FastAPI, OpenAI API, Pinecone, AWS S3, LangChain
- **Frontend**: Streamlit
- **Data Processing**: OpenAI Embeddings, PyPDF, Unstructured.io
- **Cloud Services**: AWS S3 for document storage, Pinecone for semantic search

## API Endpoints
| Endpoint | Method | Description |
|----------|--------|--------------|
| `/summarize-pdf/` | `POST` | Upload a PDF and generate a summary |
| `/qa-pdf/` | `POST` | Ask questions based on documents or general topics |
| `/fetch-research-papers/` | `POST` | Retrieve relevant research papers |
| `/publications/` | `GET` | Get available stored documents |

## Results
Quantum Computing Tutor provides an **AI-driven** approach to exploring quantum computing concepts, enabling users to **learn, summarize, and retrieve information efficiently**.

## Author
- **Sanika Dhayabar Patil**


