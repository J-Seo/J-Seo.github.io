---
layout: post
title: "Word-Level Quality Estimation for Korean-English Neural Machine Translation (IEEE Access 2022)"
date: 2022-04-21
Journal: IEEE Access
---
**IEEE Access** 
- Impact Factor 2022: 3.47

**Authors**

- Sugyeong Eo, Chanjun Park, Hyeonseok Moon, **Jaehyung Seo**, Heuiseok Lim*

**Abstract**

Quality estimation (QE) task aims to predict the machine translation (MT) quality well by referring to the source sentence and its MT output. The various applicability of QE proves the importance of QE research, but the enormous human labor to construct the QE dataset remains a challenge. This study proposes three automatic word-level pseudo-QE data construction strategies using a monolingual or parallel corpus and an external machine translator without human labor. We utilize these individual pseudo-QE datasets to finetune multilingual pretrained language models such as cross-lingual language models (XLM), XLM-RoBERTa, and multilingual BART and comparatively analyze the results. Considering the synthetic dataset creation setup, we attempt to validate the objectivity of the QE model by leveraging four test sets translated by external translators from Google, Amazon, Microsoft, and Systran. As a result, XLM-R-large shows the best performance among mPLMs. We also verify the reliability of the QE model through the close performance gaps between different test sets. To the best of our knowledge, this is the first study to experiment with word-level Korean-English QE.

Check out the [This Link][DOI] for more info on our paper. 

[DOI]: https://doi.org/10.1109/ACCESS.2022.3169155
[jekyll-gh]: https://github.com/jekyll/jekyll
