# Medical_chatbot

This chatbot is designed to provide users with reliable medical information, drawing from a combination of advanced AI and authoritative sources.

AI-Powered Responses: Leverages Langchain to process user queries and generate accurate, contextually relevant responses.

Knowledge Base:Embeddings generated using Hugging Face models for semantic understanding.Information stored and retrieved efficiently using Pinecone vector database.

Authoritative Source: Enriched with data from the Gale Encyclopedia of Medicine, ensuring responses are grounded in established medical knowledge.How it Works The user enters a medical query.

Langchain processes the query.

Hugging Face embeddings capture the semantic meaning of the query.

Pinecone retrieves the most relevant information from the knowledge base (data from the Gale Encyclopedia of Medicine).

Langchain uses this information to generate a comprehensive response.



Techstack Used:
Python
LangChain
Flask
Groq
Pinecone


