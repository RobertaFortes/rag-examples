# RAG with LangChain using the book "Os Sertões"

This project implements three Retrieval-Augmented Generation (RAG) approaches applied to the book Os Sertões, by Euclides da Cunha. The goal is to compare different context retrieval and response generation strategies using OpenAI LLMs.

## 📁 Project structure

```
.
├── data/
│   └── os-sertoes.pdf             # Input PDF (base book)
│
├── notebooks/
│   ├── naiveRAG.ipynb             # Basic approach
│   ├── parentRAG.ipynb            # Parent Document RAG
│   └── rerankRAG.ipynb            # RAG with context reranker
│
├── requirements.txt               # Libraries used
├── .gitignore
├── .env                           # API key (not tracked)
└── README.md
```

## ✅ Prerequisites

- Python 3.10+
- OpenAI API Key
- Virtual environment recommended

  
## 🛠️ How to run

- Create a `.env` file in the root directory with your OpenAI API key:
```bash
OPENAI_API_KEY=sk-xxxxx
```

- Install the required dependencies:
```bash
pip install -r requirements.txt
```

## 🔍 Notes
- The file os-sertoes.pdf is included in the data/ folder as the source document.
- The vector database (db/, chroma/, etc.) is not included in the repository and will be generated automatically when you run the notebooks.
- Chunking strategies have been adjusted to preserve semantic coherence in long literary texts.