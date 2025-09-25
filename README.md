NoteBot

NoteBot is a Streamlit-based web app that lets you upload your PDF notes and ask questions about them.
It uses LangChain, OpenAI embeddings, and FAISS vector store to split your notes into chunks, embed them, and perform semantic search. The most relevant chunks are then passed to GPT-3.5-Turbo, which answers your questions based on the content of your notes.

⚡ Features

Upload PDF notes and extract text automatically

Semantic search powered by FAISS

Ask natural language questions about your notes

Custom prompt with fallback response ("I don't know")

Runs entirely in a Streamlit app
