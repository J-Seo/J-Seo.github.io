---
layout: post
title: "Reading Comprehension requiring Discrete Reasoning Over Paragraphs for Korean (HCLT 2021)"
date: 2021-10-14
Journal: Annual Conference on Human and Language Technology 
---
**Annual Conference on Human and Language Technology (HCLT)** 

**Authors**

- Gyeong-min Kim, **Jaehyung Seo**, Soomin Lee, Heui-seok Lim

**Abstract**

기계 독해는 단락과 질의가 주어졌을 때 단락 내 정답을 찾는 자연어 처리 태스크이다. 최근 벤치마킹 데이터셋에서 사전학습 언어모델을 기반으로 빠른 발전을 보이며 특정 데이터셋에서 인간의 성능을 뛰어넘는 성과를 거두고 있다. 그러나 이는 단락 내 범위(span)에서 추출된 정보에 관한 것으로, 실제 연산을 요구하는 질의에 대한 응답에는 한계가 있다. 본 논문에서는 기존 범위 내에서 응답이 가능할 뿐만이 아니라, 연산에 관한 이산 추론을 요구하는 단락 및 질의에 대해서도 응답이 가능한 기계 독해 모델의 효과성을 검증하고자 한다. 이를 위해 영어 DROP (Discrete Reasoning Over the content of Paragraphs, DROP) 데이터셋으로부터 1,794개의 질의응답 쌍을 Google Translator API v2를 사용하여 한국어로 번역 및 정제하여 KoDROP (Korean DROP, KoDROP) 데이터셋을 구축하였다. 단락 및 질의를 참조하여 연산을 수행하기 위한 의미 태그를 한국어 KoBERT 및 KoELECTRA에 접목하여, 숫자 인식이 가능한 KoNABERT, KoNAELECTRA 모델을 생성하였다. 실험 결과, KoDROP 데이터셋은 기존 기계 독해 데이터셋과 비교하여 단락에 대한 더욱 포괄적인 이해와 연산 정보를 요구하였으며, 가장 높은 성능을 기록한 KoNAELECTRA는 KoBERT과 비교하여 F1, EM에서 모두 19.20의 월등한 성능 향상을 보였다.

Check out the [This Link][DOI] for more info on our paper. 

[DOI]: https://koreascience.kr/article/CFKO202130060719834.page
[jekyll-gh]: https://github.com/jekyll/jekyll
