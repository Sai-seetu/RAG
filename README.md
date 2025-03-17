# RAG

Chatbot using Retrieval-Augmented Generation (RAG)
This project implements a RAG-based chatbot for answering restaurant-related queries using Llama-2-7B. It combines retrieval-based search with LLM-generated responses to provide accurate and context-aware answers.

Features
✅ Data Ingestion: Loads and processes restaurant-related text from PDFs and TXT files.
✅ Vector Storage: Embeds and stores documents in FAISS for efficient retrieval.
✅ Retrieval & Query Processing: Uses RetrievalQA to fetch relevant documents.
✅ LLM Integration: Utilizes Llama-2-7B to generate responses.
✅ Fallback Mechanism: Handles unknown queries by leveraging LLM general knowledge.

Challenges & Solutions
⚡ Storage Constraints: Due to Colab storage limits, opted for 7B over 13B.
⚡ Response Accuracy: Working on improving document retrieval & fallback mechanisms.

Future Enhancements
🚀 Implement hybrid search for better retrieval.
🚀 Improve LLM-based responses for unknown queries.
🚀 Explore fine-tuning for domain-specific accuracy.

![_- visual selection](https://github.com/user-attachments/assets/ca4a3c20-784b-47bd-a00b-9db284c3ed60)
