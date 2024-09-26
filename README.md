# Document Insight AI

Document Insight AI is an advanced chatbot application that processes PDF documents and generates accurate, contextually relevant answers to user queries. Built with the Retrieval-Augmented Generation (RAG) framework, it leverages Google’s Generative AI (Gemini-Pro) model for high-quality answers and FAISS for efficient vector-based searching.

## Features

- **PDF Document Processing**: Upload multiple PDFs to extract and analyze content.
- **Contextual Q&A**: Ask questions based on the content of the uploaded documents.
- **Searchable Vector Store**: Uses FAISS to create a vector store of document embeddings for fast and efficient searches.
- **Generative AI Integration**: Powered by Google Generative AI (Gemini-Pro) for generating accurate answers.

## How It Works

1. **Upload PDF Files**: The system accepts multiple PDF files.
2. **Document Processing**: The uploaded documents are split into manageable chunks and stored in a searchable vector store using FAISS.
3. **Ask Questions**: Users can ask any question related to the document content, and the chatbot will provide an accurate, context-aware response.
4. **Real-Time Responses**: Responses are generated in real-time using Google's Gemini-Pro model.

## Requirements

To run this project, the following dependencies are required:

- Python 3.7+
- Streamlit
- PyPDF2
- LangChain
- FAISS (for vector search)
- Google Generative AI SDK

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/document-insight-ai.git
    cd document-insight-ai
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Get your Google API Key from [Google MakerSuite](https://makersuite.google.com/app/apikey) and note it down.

4. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

## Usage

1. **Enter your Google API Key**: After starting the app, enter your Google API key to authenticate access to the Google Generative AI models.
2. **Upload PDF Files**: Use the sidebar to upload one or more PDF files.
3. **Ask a Question**: After processing, type a question related to the content of the uploaded documents in the input field.
4. **Get Answers**: The chatbot will analyze the documents and provide accurate answers based on the content.

## Technologies Used

- **Streamlit**: For building the user interface.
- **LangChain**: For text splitting and chain management.
- **FAISS**: For creating and searching a vector store of document embeddings.
- **Google Generative AI (Gemini-Pro)**: For generating answers to user queries.
- **PyPDF2**: For PDF text extraction.

## Future Enhancements

- Support for additional document formats (e.g., Word, Excel).
- Enhanced accuracy for long-form queries by improving text chunking and vector search methods.
- Integration with other AI models for varied use cases.



