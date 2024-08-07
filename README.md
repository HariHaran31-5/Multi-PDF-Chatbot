# Multi-PDF-Chatbot

The Multi-PDF Chatbot is an interactive Streamlit application that allows users to upload multiple PDF files, extract their contents, and query the text using natural language. Powered by Google Generative AI and FAISS for vector search, this chatbot provides detailed answers based on the provided PDF documents.




Features:

1) Multiple PDF Upload: Upload multiple PDF files at once for processing.
2) Text Extraction: Extract text from uploaded PDF files.
3) Chunking: Split extracted text into manageable chunks for efficient processing.
4) Vector Search: Create a vector store using FAISS for fast similarity searches.
5) Question Answering: Use Google Generative AI to answer user queries based on the content of the uploaded PDFs.
6) Interactive UI: User-friendly interface powered by Streamlit.

How It Works:

1) Upload PDFs: Users can upload multiple PDF files through the sidebar.
2) Process PDFs: The application extracts text from the PDFs, splits it into chunks, and creates a vector store using FAISS.
3) Ask Questions: Users can input questions related to the content of the uploaded PDFs.
4) Get Answers: The application uses the vector store to find relevant chunks and Google Generative AI to provide detailed answers based on the extracted text.
