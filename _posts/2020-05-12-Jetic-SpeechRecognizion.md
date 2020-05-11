---
layout: post
title: "State-of-The-Art Speech Recognition with Sequence-to-Sequence Models"
root: ../../
---
In our lab meeting tomorrow, Jetic will introduce a Sequence-to-Sequence model for Speech Recognition.
A Zoom link will be posted to Twist on the morning of the meeting. 

**State-of-The-Art Speech Recognition with Sequence-to-Sequence Models**

**Abstract:**
Attention-based encoder-decoder architectures such as Listen, Attend, and Spell (LAS), subsume the acoustic, pronunciation and language model components of a traditional automatic speech recognition (ASR) system into a single neural network. In previous work, we have shown that such architectures are comparable to state-of-the- art ASR systems on dictation tasks, but it was not clear if such architectures would be practical for more challenging tasks such as voice search. In this work, we explore a variety of structural and optimization improvements to our LAS model which significantly improve performance. On the structural side, we show that word piece models can be used instead of graphemes. We also introduce a multi-head attention architecture, which offers improvements over the commonly-used single-head attention. On the optimization side, we explore synchronous training, scheduled sampling, label smoothing, and minimum word error rate optimization, which are all shown to improve accuracy. We present results with a unidirectional LSTM encoder for streaming recognition. On a 12, 500 hour voice search task, we find that the proposed changes improve the WER from 9.2% to 5.6%, while the best conventional system achieves 6.7%; on a dictation task our model achieves a WER of 4.1% compared to 5% for the conventional system.

Tuesday, May 12th, 09:30 a.m.
