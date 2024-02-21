---
layout: post
title: "DART: Data Augmentation using Retrieval Technique (HCLT 2022)"
date: 2022-10-18
Journal: HCLT 2022
---

**Authors**
- Seungjun Lee, **Jaehyung Seo**, Jungseob Lee, Myunghoon Kang, Hyeonseok Moon, Chanjun Park, Dahyun Jung, Jaewook Lee, Kinam Park, Heuiseok Lim

**Abstract**

최근 BERT 와 같은 트랜스포머 (Transformer) 기반의 모델이 natural language understanding (NLU) 와 같은 여러 자연어 처리 태스크에서 좋은 성능을 보인다. 이러한 모델은 여전히 대용량의 학습을 요구한다. 일반적으로, 데이터 증강 기법은 low-resource 환경을 개선하는 데 도움을 준다. 최근 생성 모델을 활용해 합성 데이터를 생성해 데이터를 증강하는 시도가 이루어졌다. 이러한 방법은 원본 문장과 의미론적 유사성을 훼손하지 않으면서 어휘와 구조적 다양성을 높이는 것을 목표로 한다. 본 논문은 task-oriented 한 어휘와 구조를 고려한 데이터 증강 방법을 제안한다. 이를 위해 검색 모델과 사전 학습된 생성 모델을 활용한다. 검색 모델을 사용해 학습 데이터셋의 입력 문장과 유사한 문장 쌍을 검색 (retrieval) 한다. 검색된 유사한 문장 쌍을 사용하여 생성 모델을 학습해 합성 데이터를 생성한다. 본 논문의 방법론은 low-resource 환경에서 베이스라인 성능을 최대 4% 이상 향상할 수 있었으며, 기존의 데이터 증강 방법론보다 높은 성능 향상을 보인다.

Check out the [This Link][DOI] for more info on our paper

[DOI]: https://koreascience.kr/article/CFKO202226455346012.page

