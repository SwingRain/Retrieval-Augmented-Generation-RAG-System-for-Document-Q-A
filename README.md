# Retrieval-Augmented-Generation-RAG-System-for-Document-Q-A

Developed a RAG system leveraging Meta’s Llama3 and Langchain, combined with ChromaDB to enable real-time question answering on untrained document data. Implemented a retriever-generator pipeline for efficient query processing, employing:

ChromaDB for vector-based document retrieval using embeddings.
Llama3 as the generator, configured with BitsAndBytes quantization to reduce memory usage.
Langchain for seamless orchestration of document loading, text splitting, and embedding creation.
