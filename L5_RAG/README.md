LEVEL 5 — RAG

This is extremely important for an enterprise AI engineer.

RAG:

Retrieval-Augmented Generation

Architecture:

                Documents
                    |
                    ↓
              Chunk documents
                    |
                    ↓
                Embeddings
                    |
                    ↓
              Vector Database
                    |
User Question ──────┤
                    ↓
                 Retrieval
                    |
                    ↓
              Relevant Context
                    |
                    ↓
                  LLM
                    |
                    ↓
                 Answer

Learn:

Document ingestion
Chunking
Embeddings
Vector search
Semantic search
Metadata filtering
Hybrid search
Reranking
Context window
Grounding
Hallucination

Learn at least one vector database deeply:

pgvector
Pinecone
OpenSearch
Weaviate
Milvus

I would personally start with:

PostgreSQL + pgvector

because it teaches you how vector search integrates with normal enterprise data.