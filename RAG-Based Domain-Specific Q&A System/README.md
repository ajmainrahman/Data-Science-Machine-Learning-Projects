# RAG-Based Domain-Specific Q&A

-----
**What:** Chatbot that answers questions from uploaded documents

**Tools:** LangChain + FAISS/ChromaDB + OpenAI

**Steps:**
1. Parse PDF → Chunk text → Embed → Store in Vector DB
2. Use Retrieval-Augmented Generation (RAG)
3. Optional: Add file upload UI (Gradio/Streamlit)


