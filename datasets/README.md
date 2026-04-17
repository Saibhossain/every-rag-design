# 📖 Description

**rag-practice** is a curated collection of research papers in PDF format designed for experimenting with and improving **Retrieval-Augmented Generation (RAG)** pipelines. The dataset includes documents from multiple domains to simulate real-world retrieval scenarios where relevant and irrelevant information coexist.

This setup is particularly useful for analyzing how naive RAG systems behave when dealing with noisy, diverse, and unstructured data sources.

---
# download the dataset 
``` python
import kagglehub

path = kagglehub.dataset_download("saibhossain/rag-practice")

print("Path to dataset files:", path)
```


# 🎯 Purpose

This dataset is created to help:

- Practice building end-to-end RAG systems  
- Evaluate retrieval accuracy across mixed domains  
- Understand limitations of naive RAG approaches  
- Experiment with improvements like reranking, better chunking, and hybrid search  

---

# 🗂️ Dataset Structure

- 📄 **Format:** PDF  
- 📚 **Type:** Research Papers  
- 🌐 **Domains:** Mixed (AI, NLP, Software, Healthcare, Finance, etc.)  

All files are kept in raw format to reflect real-world document ingestion challenges.

---

# ⚠️ Key Features

- Multi-domain content → introduces retrieval noise  
- Long documents → tests chunking strategies  
- Mixed relevance → challenges embedding-based retrieval  
- Unprocessed PDFs → requires custom preprocessing  

---

# 🔬 Use Cases

- RAG system development  
- Document retrieval experiments  
- Embedding model evaluation  
- FAISS / vector database testing  
- Research in LLM + IR systems  


> This file contains a collection of research papers in PDF format used for practicing and evaluating Retrieval-Augmented Generation (RAG) systems.

> The documents span multiple domains, including AI, NLP, software engineering, healthcare, and finance. They are intentionally kept in raw and unprocessed form to simulate real-world data ingestion scenarios.

> This makes the file useful for testing document loading, text extraction, chunking strategies, embedding generation, and retrieval performance in RAG pipelines.