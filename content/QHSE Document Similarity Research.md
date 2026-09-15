---
title: QHSE Document Similarity Research
date: 2025-04-15
tags:
  - project
  - ai
  - nlp
  - python
  - fastapi
  - react
---

## QHSE Document Similarity Research

A document similarity and semantic-matching project built to reduce duplication and version-control risk across the QHSE software ecosystem.

### Project Overview

This research and product prototype addresses a recurring business issue across internal QHSE workflows: duplicated, reformulated, or near-identical client documents create redundancy, data inconsistency, and operational friction. The solution evaluates and compares document similarity using multiple methods and identifies the most reliable, explainable approach.

### Key Achievements

- Benchmarked five similarity architectures: **Jaccard**, **TF-IDF**, **BM25**, **Sentence-BERT**, and **E5**
- Built a ground-truth evaluation set with **360 document pairs** (270 dev / 90 test)
- Identified and fixed an aggregation bias that inflated similarity scores for unrelated documents
- Recommended a **hybrid E5 + TF-IDF approach** balancing semantic matching and lexical precision
- Developed a working demo application with **FastAPI**, **PostgreSQL**, **React**, and **Docker**

### Business Impact

- Reduced duplication risk across QHSE document workflows
- Improved detection of near-duplicate and paraphrased client files
- Created a more reliable document comparison pipeline for enterprise use cases

### Tech Stack

- **AI / NLP:** Sentence-BERT, E5, TF-IDF, BM25, Jaccard similarity
- **Backend:** Python, FastAPI, PostgreSQL
- **Frontend:** React, Vite
- **Deployment:** Docker, GitLab CI/CD, Azure-aligned infrastructure

### What I learned

- Designing and benchmarking document-similarity systems in real business contexts
- Diagnosing model bias and improving evaluation quality with grounded error analysis
- Bridging research and deployment with an operational demo app
- Building business-facing AI solutions inside a structured enterprise workflow

### Resources

- **GitHub Repository:** [samersec/qhse-document-similarity](https://github.com/samersec/document-similarity-research.git)
- **Demo / Internal App:** Built for QHSE software suite validation and operational testing