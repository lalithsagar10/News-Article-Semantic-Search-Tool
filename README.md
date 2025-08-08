# Article-Semantic-Search-Tool
News Article Retrieval and Query System is a Streamlit app that leverages LangChain, OpenAI embeddings, and FAISS vector database to efficiently process and search news articles from URLs. It enables users to ask questions and get precise answers backed by the source content.

## Features

- Load URLs manually or upload text files containing multiple URLs.
- Fetch and process article content via LangChain's `UnstructuredURLLoader`.
- Generate embedding vectors for the articles using OpenAI embeddings.
- Use FAISS for fast and efficient similarity search and retrieval.
- Store and index embeddings locally in pickle format for reuse.
- Query the indexed articles through an interactive ChatGPT interface.
- View answers with references to source URLs.

---

## Getting Started

### Prerequisites

- Python 3.8+
- OpenAI API key (set as environment variable `OPENAI_API_KEY`)
- Required Python packages (see Installation)

Technologies Used
Streamlit — Web app framework

LangChain — Content loading and processing

OpenAI Embeddings — Embedding generation

FAISS — Vector database for similarity search and indexing

ChatGPT — Query answering via LLM
