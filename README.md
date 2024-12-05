# Chat with PDF using Gemini 💬📄

This project is a Streamlit-based application that allows users to upload PDF documents and ask questions about their content. The application uses **Google's Gemini/LLMs** for natural language understanding and FAISS for document vectorization, making it easy to extract and query information from uploaded PDFs.

---

## Features
- **PDF Upload:** Users can upload multiple PDF files for processing.
- **Text Extraction:** Extracts text content from PDF files.
- **Text Chunking:** Splits large texts into manageable chunks for better query handling.
- **Embedding Creation:** Generates embeddings for text chunks using Google Generative AI Embeddings.
- **Conversational QA:** Answers user queries using the context from the uploaded PDFs with accurate results.
- **Streamlit Interface:** User-friendly UI to interact with the application.

---

## Technologies Used
- **[Streamlit](https://streamlit.io):** Web application framework for interactive UIs.
- **[PyPDF2](https://pypi.org/project/PyPDF2/):** PDF text extraction.
- **[LangChain](https://www.langchain.com):** Text processing and chain management.
- **[Google Generative AI](https://developers.generativeai.google):** LLM and embeddings generation.
- **[FAISS](https://github.com/facebookresearch/faiss):** Efficient vector search and retrieval.

---

## Installation

### Prerequisites
1. Python 3.8 or above
2. A valid **Google API Key** for using Google's Generative AI services.

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/chat-pdf-gemini.git
   cd chat-pdf-gemini
