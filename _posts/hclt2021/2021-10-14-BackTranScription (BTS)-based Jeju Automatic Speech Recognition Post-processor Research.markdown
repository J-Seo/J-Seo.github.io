---
layout: post
title: "BackTranScription (BTS)-based Jeju Automatic Speech Recognition Post-processor Research (HCLT 2021)"
date: 2021-10-14
Journal: Annual Conference on Human and Language Technology 
---
**Annual Conference on Human and Language Technology (HCLT)** 

**Authors**

- Chanjun Park, **Jaehyung Seo**, Seolhwa Lee, Heonseok Moon, Sugyeong Eo, Yoonna Jang, Heuiseok Lim

**Abstract**

Sequence to sequence(S2S) 기반 음성인식 후처리기를 훈련하기 위한 학습 데이터 구축을 위해 (음성인식 결과(speech recognition sentence), 전사자(phonetic transcriptor)가 수정한 문장(Human post edit sentence))의 병렬 말뭉치가 필요하며 이를 위해 많은 노동력(human-labor)이 소요된다. BackTranScription (BTS)이란 기존 S2S기반 음성인식 후처리기의 한계점을 완화하기 위해 제안된 데이터 구축 방법론이며 Text-To-Speech(TTS)와 Speech-To-Text(STT) 기술을 결합하여 pseudo 병렬 말뭉치를 생성하는 기술을 의미한다. 해당 방법론은 전사자의 역할을 없애고 방대한 양의 학습 데이터를 자동으로 생성할 수 있기에 데이터 구축에 있어서 시간과 비용을 단축 할 수 있다. 본 논문은 BTS를 바탕으로 제주어 도메인에 특화된 음성인식 후처리기의 성능을 향상시키기 위하여 모델 수정(model modification)을 통해 성능을 향상시키는 모델 중심 접근(model-centric) 방법론과 모델 수정 없이 데이터의 양과 질을 고려하여 성능을 향상시키는 데이터 중심 접근(data-centric) 방법론에 대한 비교 분석을 진행하였다. 실험결과 모델 교정없이 데이터 중심 접근 방법론을 적용하는 것이 성능 향상에 더 도움이 됨을 알 수 있었으며 모델 중심 접근 방법론의 부정적 측면 (negative result)에 대해서 분석을 진행하였다.

Check out the [This Link][DOI] for more info on our paper. 

[DOI]: https://koreascience.kr/article/CFKO202130060579804.page
[jekyll-gh]: https://github.com/jekyll/jekyll
