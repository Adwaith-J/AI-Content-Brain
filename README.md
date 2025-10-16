# AI Content Brain — Free RAG-based Idea Generator

**Description:**  
AI Content Brain is a Retrieval-Augmented Generation (RAG) system that helps you generate creative ideas and answer queries based on a custom knowledge base. This project uses **HuggingFace embeddings** and **HuggingFace LLMs**, making it **fully free** and runnable offline without any OpenAI API key.


## Problem Statement

Traditional AI generation often “hallucinates” information or gives generic responses.  
By combining **retrieval from a knowledge base** with **AI generation**, RAG improves accuracy, context, and relevance.

**Goal:** Build a free, offline-capable AI tool that can:
- Generate innovative ideas
- Provide answers grounded in documents
- Work without any paid API



## Tech Stack

| Component | Tool / Library |
|-----------|----------------|
| Programming Language | Python 3.x |
| AI Generation | HuggingFace Transformers (`flan-t5-small`) |
| Embeddings | HuggingFace Sentence Transformers (`all-MiniLM-L6-v2`) |
| Vector Database | FAISS |
| RAG Framework | LangChain & LangChain-HuggingFace |
| Notebook | VS Code Jupyter / Colab |

## Output

<img width="1679" height="313" alt="image" src="https://github.com/user-attachments/assets/711856d8-32d6-4d5c-80af-00b3b17df83c" />


## Installation & Setup

1. **Clone the repository**:
```bash
git clone https://github.com/your-username/ai-content-brain.git
cd ai-content-brain

