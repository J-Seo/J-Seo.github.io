---
layout: post
title: "BTS: Back TranScription for Speech-to-Text Post-Processor using Text-to-Speech-to-Text (WAT2021)"
date: 2021-08-01
Conference: Proceedings of the 8th Workshop on Asian Translation (WAT2021)
categories: outstanding
---
**Authors**
- Chanjun Park, **Jaehyung Seo**, Seolhwa Lee, Chanhee Lee, Hyeonseok Moon, Sugyeong Eo, Heui-Seok Lim

**Abstract**
With the growing popularity of smart speakers, such as Amazon Alexa, speech is becoming one of the most important modes of human-computer interaction. Automatic speech recognition (ASR) is arguably the most critical component of such systems, as errors in speech recognition propagate to the downstream components and drastically degrade the user experience. A simple and effective way to improve the speech recognition accuracy is to apply automatic post-processor to the recognition result. However, training a post-processor requires parallel corpora created by human annotators, which are expensive and not scalable. To alleviate this problem, we propose Back TranScription (BTS), a denoising-based method that can create such corpora without human labor. Using a raw corpus, BTS corrupts the text using Text-to-Speech (TTS) and Speech-to-Text (STT) systems. Then, a post-processing model can be trained to reconstruct the original text given the corrupted input. Quantitative and qualitative evaluations show that a post-processor trained using our approach is highly effective in fixing non-trivial speech recognition errors such as mishandling foreign words. We present the generated parallel corpus and post-processing platform to make our results publicly available.

Check out the [This Link][DOI] for more info on our paper

[DOI]: https://aclanthology.org/2021.wat-1.10/

