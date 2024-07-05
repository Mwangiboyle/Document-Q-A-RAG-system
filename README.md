# Gemma Document Q & A Chatbot

![image](https://github.com/Mwangiboyle/Document-Q-A-RAG-system/assets/92526613/28dc9848-c088-43f6-9c43-14fd95848dc7)
## Importance

In today's information-rich world, efficient retrieval and accurate interpretation of information are crucial. The Gemma Document Q & A Chatbot addresses this need by leveraging Retrieval-Augmented Generation (RAG) to provide precise answers to user queries based on the contents of documents. This system can be especially useful for organizations that manage large volumes of documents, enabling quick access to relevant information and enhancing productivity.

## Overview

The Gemma Document Q & A Chatbot is an advanced system designed to answer questions by processing and understanding the content of documents. It uses a combination of document loaders, text splitting, embeddings, vector stores, and language models to deliver accurate and contextually relevant answers.

## Features

- **Document Loading**: Load documents from various sources, including YouTube transcripts.
- **Text Splitting**: Split documents into manageable chunks for processing.
- **Embeddings**: Use embeddings to represent document chunks in a vector space.
- **Vector Store**: Utilize FAISS for efficient similarity searches.
- **Language Model**: Generate answers using advanced language models.
- **User Interface**: Intuitive interface for asking questions and viewing responses.

## Installation

To run the Gemma Document Q & A Chatbot, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://https://github.com/Mwangiboyle/Document-Q-A-RAG-system.git
   cd Document-Q-A-RAG-system

  pip install -r requirements.txt

  streamlit run app.py

Usage
Load a Document:
Enter the URL of the document or YouTube video transcript you want to load.

Ask a Question:
Type your question in the input box and click the "Ask" button.

View the Answer:
The chatbot will display the answer based on the document's content.
