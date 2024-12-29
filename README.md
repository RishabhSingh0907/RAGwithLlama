# Project Overview 
This project integrates the Llama-index, a large language model index, with a vector database (Faiss) to develop a Retrieval-Augmented Generator (RAG) agent. The RAG agent is designed to extract information from documents and perform question answering on the provided document.

### Project Structure
mainjupyter.ipynb: The Jupyter/Colab notebook containing the implementation of the RAG agent.
Articles/: Directory containing the document dataset used for training and testing.

### Implementation Details
The RAG agent consists of two main components:
Retriever: Uses Faiss to index and retrieve relevant documents based on the input query.
Generator: Leverages the Llama-index to generate a response based on the retrieved documents.

### Usage
Clone the repository and navigate to the project directory.
Run the Jupyter/Colab notebook to train and test the RAG agent.
