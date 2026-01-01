# 🧠 RAG_Project  
*A collection of experiments, techniques, and workflows for building Retrieval-Augmented Generation systems.*

This repository is a **personal sandbox** for exploring different components of Retrieval-Augmented Generation (RAG).  
Each folder represents a standalone experiment or technique, letting you independently study ingestion, chunking, embeddings, vector databases, hybrid search, query enhancement, and multimodal pipelines.

---

## 🚀 Goals

- Practice and understand core RAG building blocks  
- Explore chunking, embeddings, vector databases, and hybrid retrieval  
- Improve retrieval quality through experiments  
- Try multimodal RAG (images, PDFs, OCR)  
- Build a modular, plug-and-play RAG workflow

This is **not** a production system — it's a learning-focused research playground.

---

## 📁 Folder Structure

```

RAG_Project/
│
├── 0-DataIngestParsing/            # Raw data loading, cleaning & preprocessing
├── AdvanceChunking/                # Token-based, semantic, recursive chunking
├── HybridSearchStratergies/        # Keyword + semantic + hybrid retrieval
├── QueryEnhancement/               # Query rewriting, expansion & reformulation
├── VectorEmbedding/                # Embedding models & embedding utilities
├── VectorStore/                    # Vector DB tests, benchmarks & wrappers
├── multimodal/                     # OCR, image embeddings, multimodal RAG
│
├── main.py                         # Optional pipeline runner / tests
├── requirements.txt                # Dependencies
├── VectorStore+VectorDatabases.pdf # Study notes
└── README.md

````

---

## 🔧 Installation

### Using `pip`
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
````

### Using `uv` (faster)

```bash
uv pip install -r requirements.txt
```

---

## 🧪 Usage

This repository is modular — explore or run each component individually.

### Example: Data ingestion

```bash
python 0-DataIngestParsing/ingest.py
```

### Example: Chunking logic

```bash
python AdvanceChunking/chunk_test.py
```

### Example: Embedding generation

```bash
python VectorEmbedding/embed.py
```

### Example: Vector store retrieval

```bash
python VectorStore/search.py
```

---

## 🧱 RAG Components

### ✔ Data Ingestion

* PDF / text parsing
* Cleaning & normalization
* Metadata extraction

### ✔ Chunking Techniques

* Fixed-size
* Recursive splitting
* Sentence-aware
* Semantic chunking

### ✔ Embedding Models

* OpenAI
* HuggingFace
* Instructor models
* Multimodal embeddings

### ✔ Vector Stores

* FAISS
* Chroma
* Pinecone (optional)
* In-memory stores

### ✔ Hybrid Search

* BM25 + embeddings
* Reciprocal Rank Fusion (RRF)
* Weighted scoring

### ✔ Query Enhancement

* LLM-based query rewriting
* Expansion (synonyms, keywords)
* Clarification prompts

### ✔ Multimodal

* OCR pipelines
* Image embeddings
* Vision-language models

---

## 📚 Purpose

This repository acts as a **learning journal** for building RAG systems.
It gives you a flexible foundation you can later turn into a production pipeline if you choose.

---

## 🗺️ Future Improvements

* Unified pipeline using `main.py`
* Retrieval benchmarks & evaluation
* Visualizations (embedding plots, retrieval maps)
* LLM integration for generation tasks
* Dataset-based retrieval evaluation metrics

---
