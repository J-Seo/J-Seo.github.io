---
layout: post
title: "Length-aware Byte Pair Encoding for Mitigating Over-segmentation in Korean Machine Translation"
date: 2024-07-31
Journal: ACL 2024 - Findings
categories: outstanding
image: "https://raw.githubusercontent.com/J-Seo/J-Seo.github.io/main/assets/img/acl2024.png"
authors: Jungseob Lee, Hyeonseok Moon, Seungjun Lee Chanjun Park, Sugyeong Eo, Hyunwoong Ko, Jaehyung Seo, Seungyoon Lee, Heuiseok Lim
---
**Authors**
- Jungseob Lee, Hyeonseok Moon, Seungjun Lee Chanjun Park, Sugyeong Eo, Hyunwoong Ko, **Jaehyung Seo**, Seungyoon Lee, Heuiseok Lim

**Abstract**
Byte Pair Encoding is an effective approach in machine translation across several languages. 
However, our analysis indicates that BPE is prone to over-segmentation in the morphologically rich language, Korean, which can erode word semantics and lead to semantic confusion during training. 
This semantic confusion, stemming from over-segmentation, ultimately contributes to a degradation of overall translation quality. 
To address this issue, we introduce Length-aware Subword Vocabulary Construction (LeVoC), a novel approach strategically incorporating longer words into the vocabulary. 
By utilizing an external monolingual Korean corpus, LeVoC extracts and integrates long words, effectively preserving morphological information and reducing semantic confusion. 
Our experiments demonstrate that LeVoC not only significantly outperforms BPE, but also can be applied to and surpass current state-of-the-art morpheme-aware subword tokenization methods. 
We provide evidence that the difficulty in translating sentences with long words in Korean is associated with morphological compositionality, 
and LeVoC's ability to reduce semantic confusion during training leads to improved translation quality.

Check out the [This Link][DOI] for more info on our paper

[DOI]: https://aclanthology.org/2024.findings-acl.135/

