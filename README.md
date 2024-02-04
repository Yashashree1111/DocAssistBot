DocAssistBot

DocAssistBot is a Streamlit-based chat application that allows users to interact with multiple PDF documents using natural language queries. The bot leverages language models and vector embeddings to provide conversational responses based on the content of the uploaded PDFs.

Features:
PDF Processing: Upload multiple PDF documents and interactively query their content.
Conversational AI: Utilize advanced language models to generate conversational responses.
Vector Embeddings: Employ OpenAI Embeddings and FAISS vector stores to represent and retrieve information from document chunks.
Memory Management: Maintain a conversation history using a ConversationBufferMemory.

Usage:

Upload PDFs: Use the file uploader to upload one or more PDF documents.
Ask a Question: Enter your question about the documents in the text input field.
Process: Click the "Process" button to analyze the PDFs and receive chat-based responses.

Dependencies:
Streamlit
dotenv
PyPDF2
langchain
FAISS
HuggingFace Transformers

Credits:
The project utilizes language models and vector embeddings from OpenAI and Hugging Face.
Streamlit is the primary framework for the user interface.
