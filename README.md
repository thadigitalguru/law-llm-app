# Law LLM API

A FastAPI-powered Legal Question Answering API with document upload support, LangChain integration, and OpenAI backend.

## Features
- Upload PDFs or DOCX legal files
- Extract and save text
- Secure API with bearer tokens
- Prepare for LangChain + FAISS vector DB

## Run Locally
```bash
uvicorn app.main:app --reload
```

## Auth
Use `Authorization: Bearer your-secret-token` in headers.
