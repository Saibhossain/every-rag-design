# 🚀 Exploring the Limits of Hybrid RAG → What I Learned

Recently, I worked on improving a Retrieval-Augmented Generation (RAG) system using a Document-aware Hybrid RAG approach.
The idea was simple:

Instead of searching across all documents, first select the most relevant papers, then retrieve chunks only from those papers.
* ✅ This helped reduce noise a lot
* ✅ Answers became more focused
* ✅ Multi-domain confusion almost disappeared

But here’s the interesting part…
> 👉 Even after improving retrieval, the system still fails in some cases.

## 🔍 Where it works well
* When the query clearly mentions a specific paper
* When the answer exists explicitly in one section
* When the question is direct (methods, definitions, etc.)

## ⚠️ Where it still fails
* When the query is ambiguous (“the lung cancer paper”)
* When information is spread across multiple sections (like limitations)
* When comparing two papers
* When the system needs to decide which paper the user means

## 💡 Key insight:
* Hybrid RAG fails due to wrong retrieval
* Document-aware Hybrid RAG fails due to reasoning & synthesis limitations

So the bottleneck has shifted:
> ➡️ From retrieval problem → to understanding + reasoning problem

## 📊 My Takeaway
* Improving retrieval alone is not enough.
* To go further, we need:
* Better document disambiguation
* Balanced evidence from multiple papers
* Query-aware pipelines (fact, comparison, summary)
* Stronger answer synthesis

## 📎 I’ve shared my experiments here:
> 🔗 Notebook 1: https://www.kaggle.com/code/saibhossain/hybrid-rag

> 🔗 Notebook 2: [https://www.kaggle.com/code/saibhossain/document-aware-hybrid-rag

If you're working on RAG systems, especially with research papers or multi-document setups, you’ll likely hit this boundary too.
Would love to hear your thoughts or approaches to solve this 🚀

