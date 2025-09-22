# RAG systems
## 📌 Key Objectives

This repo provides an easy, step-by-step guide for building and evaluating Retrieval-Augmented Generation (RAG) systems.

Currently, it includes:

- A Simple RAG pipeline notebook (end-to-end workflow).
- An Evaluation notebook (LLM-as-a-judge approach for assessing RAG outputs).

## 🗂️ Repo Structure

```├── notebooks/
│   ├── simple_rag.ipynb          # Build a simple RAG pipeline
│   ├── evaluation.ipynb          # Evaluate RAG with custom judges
├── requirements.txt              # Python dependencies
├── data/                         # Add your own PDFs or data sources here
└── .env                          # Store your API keys (not committed)
```

## ⚙️ Setup Instructions

#### 1. Clone the repo

```
git clone https://github.com/<your-username>/rag.git
cd rag
```

#### 2. Install dependencies

```
pip install -r requirements.txt
```

#### 3. Create a .env file with your access tokens (e.g. OpenAI keys):

```
OPENAI_API_KEY=your_api_key_here
```

#### 4. Prepare a data/ folder and add your documents (e.g. PDFs) for retrieval.


## 📊 Pipeline Diagrams

### Simple RAG Pipeline
<img width="1400" height="724" alt="image" src="https://github.com/user-attachments/assets/41199ce3-fcab-4054-8e54-4f4c4e582d26" />

### Evaluation Judges
<img width="1400" height="642" alt="image" src="https://github.com/user-attachments/assets/552f4f20-ef96-4d2c-ab5f-d1fcd3d20d13" />
