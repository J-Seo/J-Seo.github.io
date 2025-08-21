---
layout: post
title: "MultiDocFusion : Hierarchical and Multimodal Chunking Pipeline for Enhanced RAG on Long Industrial Documents"
date: 2025-08-20
image: "https://raw.githubusercontent.com/J-Seo/J-Seo.github.io/main/assets/img/emnlp2025.png"
Journal: EMNLP 2025
authors: Joong Min Shin, Chanjun Park, Jeongbae Park, Jaehyung Seo, Heuiseok Lim
categories: outstanding
star: 🌟
---
**Authors**
- Joong Min Shin, Chanjun Park, Jeongbae Park, **Jaehyung Seo†**, Heuiseok Lim†

**Abstract**

Retrieval-augmented generation (RAG)-based question answering (QA) has emerged as a powerful method for processing long industrial documents. However, conventional text chunking approaches often neglect complex and long industrial document structures, causing information loss and reduced answer quality. To address this, we introduce \textbf{MultiDocFusion}, a multimodal chunking pipeline that integrates: (i) detection of document regions using vision-based document parsing, (ii) text extraction from these regions via OCR, (iii) reconstruction of document structure into a hierarchical tree using large language model (LLM)-based document section hierarchical parsing (DSHP-LLM), and (iv) construction of hierarchical chunks through DFS-based grouping. Extensive experiments across industrial benchmarks demonstrate that \textbf{MultiDocFusion} improves retrieval precision by 8–15% and ANLS QA scores by 2–3% compared to baselines, emphasizing the critical role of explicitly leveraging document hierarchy for multimodal document-based QA. These significant performance gains underscore the necessity of structure-aware chunking in enhancing the fidelity of RAG-based QA systems.

Check out the [This Link][DOI] for more info on our paper

[DOI]: TBD

