---
layout: post
title: "HiKEY: Hierarchical Multimodal Retrieval for Open-Domain Document Question Answering"
date: 2026-07-27
image: ""
Journal: ACL 2026 (Oral)
authors: Joongmin Shin, Gyuho Shim, Jeongbae Park, Jaehyung Seo*, Heuiseok Lim*
categories: outstanding
star: 🌟
---
**Authors**
- Joongmin Shin, Gyuho Shim, Jeongbae Park, **Jaehyung Seo**<sup>*</sup>, Heuiseok Lim<sup>*</sup>

**Abstract**
Retrieval-augmented generation (RAG) for document-based Open-domain Question Answering (ODQA) on large-scale industrial corpora faces two critical bottlenecks: routing failure in locating the correct document and evidence fragmentation in integrating scattered information. Existing approaches relying on flat text chunks or page-level images inherently struggle to (i) precisely pinpoint the target document among thousands of candidates and (ii) organically connect multimodal evidence, such as tables and figures, within a limited token budget. To address these challenges, we propose HiKEY, a hierarchical tree-based multimodal retrieval framework that elevates document hierarchy to a first-class retrieval signal. Instead of simple chunking, HiKEY reconstructs a logical heterogeneous graph via Document Hierarchical Parsing (DHP), explicitly encoding parent–child relationships. Adopting a hierarchical coarse-to-fine strategy, the framework (1) performs global routing to rapidly prune the search space using hierarchical indexing, and (2) conducts fine-grained retrieval to rank sections by employing a multimodal fusion strategy that captures the most discriminative evidence. Finally, HiKEY assembles a token-efficient evidence subgraph via a hybrid structural-semantic packing strategy. Experiments on ODQA benchmarks demonstrate that HiKEY significantly outperforms page- and chunk-based baselines, improving retrieval recall by up to 12.9% and end-to-end QA performance by up to 6.8%.

Paper link: TBD
