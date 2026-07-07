# DocChat – AI-Powered Document Question Answering

DocChat is a **Retrieval-Augmented Generation (RAG)** application that allows users to upload documents and ask questions in natural language. It retrieves the most relevant information from the document using vector embeddings and generates accurate, context-aware responses with an LLM.

---

## Features

- Upload PDF or text documents
- Semantic search using vector embeddings
- AI-powered question answering
- Retrieval-Augmented Generation (RAG)
- Fast document retrieval with ChromaDB
- Context-aware responses using OpenAI
- Simple and user-friendly interface

---

## Tech Stack

- Python
- LangChain
- ChromaDB
- OpenAI API
- Vector Embeddings

---

## Project Structure

```text
DocChat/
│
├── app.py
├── requirements.txt
├── data/
├── chroma_db/
├── utils.py
├── README.md
└── .env
```

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/DocChat.git
```

### 2. Navigate to the project

```bash
cd DocChat
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

Windows

```bash
venv\Scripts\activate
```

macOS/Linux

```bash
source venv/bin/activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env` file and add your OpenAI API key:

```env
OPENAI_API_KEY=your_api_key_here
```

---

## Run the Application

```bash
python app.py
```

---

## How It Works

1. Upload a document.
2. The document is split into smaller chunks.
3. Each chunk is converted into vector embeddings.
4. Embeddings are stored in ChromaDB.
5. User asks a question.
6. The most relevant document chunks are retrieved.
7. OpenAI generates an answer using the retrieved context.

---

## Future Improvements

- Support multiple document uploads
- Chat history
- PDF highlighting
- Streamlit web interface
- Authentication
- Multiple LLM support
- Docker deployment

---

## Screenshots

Add screenshots of the application here.

---

## Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push to the branch.
5. Open a Pull Request.

---

## Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---



---

## Author

**Tanya Singh**

- GitHub: https://github.com/tanyasingh0307
- LinkedIn: https://www.linkedin.com/in/tanya-singh-334702271/
