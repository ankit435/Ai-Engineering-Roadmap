 # Retrieval-Augmented Generation (RAG)

Retrieval-Augmented Generation (RAG) enhances LLMs by combining them with external data sources. Instead of relying solely on a model's internal knowledge, RAG enables dynamic access to updated or domain-specific content during generation.

## Learning Objectives

By the end of this module, you should be able to:

- Understand the RAG architecture and its components (retriever + generator)
- Build a simple RAG pipeline using vector databases and LLMs
- Fine-tune retrieval systems with embeddings
- Apply RAG to real-world use cases (Q&A, chatbots, knowledge assistants)

## Why It’s Important

LLMs have limited context windows and static training data. RAG solves this by letting the model *fetch* relevant information at inference time, making it suitable for up-to-date, factual, or enterprise-specific AI systems.


## Core Topics & Resources

### 1. RAG Fundamentals

- [Retrieval-Augmented Generation – YouTube (AssemblyAI)](https://www.youtube.com/watch?v=qbIk7-JPB2c) — **Free**
- [Hugging Face RAG Architecture Overview](https://huggingface.co/blog/rag) — **Free**
- [RAG Explained – Zilliz](https://zilliz.com/blog/retrieval-augmented-generation-explained) — **Free**

Covers:
- Vector stores, retrievers, and generators
- How RAG differs from fine-tuning
- Overview of in-memory vs. persistent RAG systems

### 2. Building a RAG Pipeline

- [LangChain RAG Tutorial](https://docs.langchain.com/docs/use-cases/question-answering/) — **Free**
- [Haystack RAG Implementation](https://docs.haystack.deepset.ai/docs/rag) — **Free**
- [ChromaDB + OpenAI Demo](https://www.youtube.com/watch?v=GkZrTgV0nrw) — **Free**

Covers:
- Creating and using vector stores (Chroma, FAISS, Weaviate)
- Embedding models (OpenAI, Hugging Face, SentenceTransformers)
- Chunking, retrieval, and prompt integration

### 3. Embeddings & Vector Databases

- [OpenAI Embedding Guide](https://platform.openai.com/docs/guides/embeddings) — **Free tier available**
- [Intro to FAISS – Facebook AI](https://github.com/facebookresearch/faiss) — **Free**
- [ChromaDB Quickstart](https://docs.trychroma.com/) — **Free**

Covers:
- Text chunking, embedding creation
- Storing and searching vectors
- Semantic similarity vs. keyword search

### 4. Evaluation & Optimization

- [RAG Best Practices – Cohere](https://docs.cohere.com/docs/rag-best-practices) — **Free**
- [Prompt Engineering for RAG](https://www.promptingguide.ai/techniques/rag) — **Free**
- [Context Re-ranking with BGE/ColBERT](https://huggingface.co/spaces/mteb/leaderboard) — **Free**

Covers:
- Retrieval precision and recall
- Re-ranking strategies
- Optimizing chunk size, temperature, prompt context

### 5. Advanced RAG Resources

- [Awesome RAG (GitHub)](https://github.com/0xpayne/awesome-rag) — **Curated list**
- [RAG End-to-End Tutorial (YouTube, Pinecone)](https://www.youtube.com/watch?v=Vv0bKz0j7uY) — **Free**
- [RAG with OpenAI and ChromaDB (Blog)](https://blog.langchain.dev/rag-openai-chromadb/) — **Free**
- [RAG Evaluation and Metrics (Cohere)](https://docs.cohere.com/docs/rag-evaluation) — **Free**

Covers:
- End-to-end RAG pipelines
- Evaluation and metrics for RAG
- Open-source RAG tools and frameworks

## Suggested Projects & Practice

- Build a "Chat with Docs" tool using LangChain and FAISS
- Create a RAG-powered knowledge assistant for your notes or PDFs
- Compare keyword vs. semantic search performance in a retrieval setup
- Use Haystack or Chroma to deploy a RAG Q&A bot

## Checkpoint: Before You Move On

You should now be able to:

- Explain how RAG works and why it's used
- Build a full RAG pipeline from documents to query output
- Use vector databases and embeddings effectively
- Optimize RAG for relevance and performance

🔗 Next: [Prompt Engineering →](./04_prompt-engineering.md) 