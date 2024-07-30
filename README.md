# Multi Query RAG Application

## Overview

This project is a Multi Query Retrieval-Augmented Generation (RAG) application built with Streamlit. It allows users to upload multiple PDFs, select from various embedding models, and interact with the uploaded PDFs through a chat interface. 

The application utilizes a multi-query approach to enhance retrieval performance and provide more accurate responses based on the uploaded content.
Check it out here - https://huggingface.co/spaces/Rgoomer/Multi_Query_RAG

<img width="1335" alt="Screenshot 2024-07-30 at 5 11 28 PM" src="https://github.com/user-attachments/assets/691cab80-282c-4dca-8b0b-a873a1b36c3b">


## Features

- **Upload Multiple PDFs:** Users can upload several PDF documents at once.
- **Select Embedding Models:** Choose from BGE (BAAI), OpenAI, or Sentence Transformers for creating embeddings.
- **Create Chroma VectorStore:** The application generates a Chroma VectorStore based on the selected embedding model.
- **Interactive Chat:** Users can chat about the content of the uploaded PDFs.

## Installation

### Using Docker

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/multi-query-rag-app.git
   cd multi-query-rag-app
   ```

2. **Build the Docker Image:**
   ```bash
   docker build -t multi-query-rag-app .
   ```

3. **Run the Docker Container:**
   ```bash
   docker run -p 8501:8501 multi-query-rag-app
   ```

   The application will be accessible at `http://localhost:8501`.

## Usage

1. **Upload PDFs:**
   - Navigate to the Streamlit app in your browser.
   - Use the upload functionality to add multiple PDF files.

2. **Select Embedding Model:**
   - Choose the desired embedding model (BGE, OpenAI, or Sentence Transformers) from the available options.

3. **Interact with PDFs:**
   - Use the chat interface to ask questions and interact with the content of the uploaded PDFs.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Streamlit](https://streamlit.io/)
- [LangChain](https://www.langchain.com/)
- [Chroma](https://www.trychroma.com/)
- [BAAI](https://www.baai.ac.cn/)
- [OpenAI](https://www.openai.com/)
- [Sentence Transformers](https://www.sbert.net/)

---

Feel free to modify or expand on this as needed!
