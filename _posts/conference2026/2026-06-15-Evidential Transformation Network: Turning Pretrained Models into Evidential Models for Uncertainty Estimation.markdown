---
layout: post
title: "Evidential Transformation Network: Turning Pretrained Models into Evidential Models for Uncertainty Estimation"
date: 2026-06-15
image: "assets/images/publications/evidential_transformation_network_fig1.png"
Journal: CVPR 2026
authors: Yongchan Chun, Chanhee Park, Jeongho Yoon, Jaehyung Seo*, Heuiseok Lim*
categories: outstanding
star: 🌟
---
**Authors**
- Yongchan Chun, Chanhee Park, Jeongho Yoon, **Jaehyung Seo**<sup>*</sup>, Heuiseok Lim<sup>*</sup>

**Abstract**
Pretrained models have become standard in both vision and language, yet they typically do not provide reliable measures of confidence. Existing uncertainty estimation methods—such as deep ensembles and MC dropout—are often too computationally expensive to deploy in practice. Evidential Deep Learning (EDL) offers a more efficient alternative, but it requires models to be trained to output evidential quantities from the start, which is rarely true for pretrained networks. To enable EDL-style uncertainty estimation in pretrained models, we propose the Evidential Transformation Network (ETN), a lightweight post-hoc module that converts a pretrained predictor into an evidential model. ETN operates in logit space: it learns a sample-dependent affine transformation of the logits and interprets the transformed outputs as parameters of a Dirichlet distribution for uncertainty estimation. We evaluate ETN on image classification and large language model question-answering benchmarks, under both in-distribution and out-of-distribution settings. ETN consistently improves uncertainty estimation over post-hoc baselines, while preserving accuracy and adding only minimal computational overhead.

Paper link: TBD
