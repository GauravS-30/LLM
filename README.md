# LLM RAG Application
This is a RAG (Retrieval Augemented Generative) application built using LLama-2-7B model. I've used Chase Bank's Online Privacy policy documents.

I imported these documents using Document Loaders from Langchain and then using Chroma DB and Sentence-Transformer's embedding models to build a vestor database for quick retrieval. And lastly I used Langchain RetrievalQA chain to create a conversational chatbot. Going ahead I'll be working towards building a UI for this app using Streamlit which will let user upload there documensts and ask questions from the knowledge base.
