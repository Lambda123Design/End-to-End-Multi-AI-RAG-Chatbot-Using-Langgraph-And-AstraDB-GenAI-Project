# End-to-End-Multi-AI-RAG-Chatbot-Using-Langgraph-And-AstraDB-GenAI-Project
This Repository contains my working files of "End to End Multi AI RAG Chatbot Using Langgraph And AstraDB", an GenAI Project

(i) Implemented a multi-agent AI workflow using LandGraph, creating distinct agents for handling user queries via vector database search and external tool search.

(ii) Set up AstraDB as a cloud-based vector database, storing website content as embeddings using a sentence transformer model for efficient semantic search.

(iii) Integrated web scraping and recursive text splitting to fetch and preprocess website data, chunk it, and store it in AstraDB for vector-based retrieval.

(iv) Developed a router node in LandGraph to dynamically decide whether a query should be handled by the vector DB agent or the external tool agent (e.g., Wikipedia search).

(v) Tested and validated the complete multi-agent workflow, enabling modular, scalable, and cloud-deployable AI applications capable of answering both general knowledge and domain-specific queries.
