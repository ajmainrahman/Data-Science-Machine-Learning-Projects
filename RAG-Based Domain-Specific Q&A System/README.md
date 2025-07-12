# RAG-Based Domain-Specific Q&A

-----
**What:** Chatbot that answers questions from uploaded documents
**Tools:** LangChain + FAISS/ChromaDB + OpenAI
**Steps:**
. Parse PDF → Chunk text → Embed → Store in Vector DB
. Use Retrieval-Augmented Generation (RAG)
. Optional: Add file upload UI (Gradio/Streamlit)


