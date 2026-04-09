



    
    rag-design-space/
    │
    ├── README.md
    ├── LICENSE
    ├── requirements.txt
    ├── pyproject.toml
    ├── .gitignore
    │
    ├── docs/
    │   ├── article_overview.md
    │   ├── taxonomy_of_rag.md
    │   ├── evaluation.md
    │   ├── production_failures.md
    │   ├── agentic_rag.md
    │   └── images/
    │
    ├── datasets/
    │   ├── sample_data/
    │   └── README.md
    │
    ├── configs/
    │   ├── standard_rag.yaml
    │   ├── hybrid_rag.yaml
    │   ├── graph_rag.yaml
    │   ├── self_rag.yaml
    │   └── agentic_rag.yaml
    │
    ├── src/
    │   ├── common/
    │   │   ├── loader.py
    │   │   ├── chunking.py
    │   │   ├── embeddings.py
    │   │   ├── vectordb.py
    │   │   ├── retrievers.py
    │   │   ├── reranker.py
    │   │   ├── prompts.py
    │   │   ├── llm.py
    │   │   ├── evaluation.py
    │   │   └── utils.py
    │   │
    │   ├── standard_rag/
    │   │   ├── pipeline.py
    │   │   └── README.md
    │   │
    │   ├── hybrid_rag/
    │   │   ├── pipeline.py
    │   │   └── README.md
    │   │
    │   ├── multi_query_rag/
    │   │   ├── pipeline.py
    │   │   └── README.md
    │   │
    │   ├── hyde_rag/
    │   │   ├── pipeline.py
    │   │   └── README.md
    │   │
    │   ├── graph_rag/
    │   │   ├── pipeline.py
    │   │   ├── graph_builder.py
    │   │   └── README.md
    │   │
    │   ├── self_rag/
    │   │   ├── pipeline.py
    │   │   └── README.md
    │   │
    │   ├── agentic_rag/
    │   │   ├── pipeline.py
    │   │   ├── agents.py
    │   │   ├── tools.py
    │   │   └── README.md
    │   │
    │   └── secure_rag/
    │       ├── pipeline.py
    │       ├── policy.py
    │       └── README.md
    │
    ├── notebooks/
    │   ├── 01_standard_rag.ipynb
    │   ├── 02_hybrid_rag.ipynb
    │   ├── 03_hyde_rag.ipynb
    │   ├── 04_graph_rag.ipynb
    │   ├── 05_agentic_rag.ipynb
    │   └── 06_evaluation.ipynb
    │
    ├── benchmarks/
    │   ├── configs/
    │   ├── run_benchmark.py
    │   ├── metrics.py
    │   └── results/
    │
    └── tests/
        ├── test_chunking.py
        ├── test_retrieval.py
        ├── test_generation.py
        └── test_evaluation.py