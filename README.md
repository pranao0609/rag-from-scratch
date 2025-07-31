#  Retrieval-Augmented Generation (RAG) — From Scratch

This project implements a simplified version of **RAG (Retrieval-Augmented Generation)**, inspired by the [original Facebook AI research paper](https://arxiv.org/abs/2005.11401). It demonstrates how modern LLMs can retrieve and generate factual answers in a knowledge-augmented pipeline — without using LangChain, Haystack, or any framework wrappers.

---

##  Key Features

-  End-to-end RAG pipeline in one Colab notebook
-  **Dense Retriever** using pretrained DPR models
-  **FAISS Index** for fast similarity search
-  **BART Generator** for sequence generation
-  Easily understandable, modular code blocks

---

##  Architecture Overview

1. **Question Encoding**: Encodes input query using DPR Question Encoder
2. **Document Retrieval**: Uses FAISS to retrieve top-k similar documents from a corpus
3. **Answer Generation**: Combines retrieved documents + query and generates final answer using BART

---

