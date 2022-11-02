---
layout: post
title: "Word-level Korean-English quality estimation (HCLT 2021)"
date: 2021-10-14
Journal: Annual Conference on Human and Language Technology 
---
**Annual Conference on Human and Language Technology** 

**Authors**

- Sugyeong Eo, Chanjun Park, **Jaehyung Seo**, Hyeonseok Moon, Heuiseok Lim

**Abstract**

기계번역 품질 예측 (Quality Estimation, QE) 은 정답 문장에 대한 참조없이 소스 문장과 기계번역 결과를 통해 기계번역 결과에 대한 품질을 수준별 주석으로 나타내주는 태스크이며, 다양한 활용도가 있다는 점에서 꾸준히 연구가 수행되고 있다. 그러나 QE 모델 학습을 위한 데이터 구성 시 기계번역 결과에 대해 번역 전문가가 교정한 문장이 필요한데, 이를 제작하는 과정에서 상당한 인건비와 시간 비용이 발생하는 한계가 있다. 본 논문에서는 번역 전문가 없이 병렬 또는 단일 말뭉치와 기계번역기만을 활용하여 자동화된 방식으로 한국어-영어 합성 QE 데이터를 구축하며, 최초로 단어 수준의 한국어-영어 기계번역 결과 품질 예측 모델을 제작하였다. QE 모델 제작 시에는 Cross-lingual language model (XLM), XLM-RoBERTa (XLM-R), multilingual BART (mBART) 와 같은 다언어모델들을 활용하여 비교 실험을 수행했다. 또한 기계번역 결과에 대한 품질 예측의 객관성을 검증하고자 구글, 아마존, 마이크로소프트, 시스트란의 번역기를 활용하여 모델 평가를 진행했다. 실험 결과 XLM-R 을 활용하여 미세조정학습한 QE 모델이 가장 좋은 성능을 보였으며, 품질 예측의 객관성을 확보함으로써 QE 의 다양한 장점들을 한국어-영어 기계번역에서도 활용할 수 있도록 했다.

Check out the [This Link][DOI] for more info on our paper. 

[DOI]: https://koreascience.kr/article/CFKO202130060780846.page
[jekyll-gh]: https://github.com/jekyll/jekyll
