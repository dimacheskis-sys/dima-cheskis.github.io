---
layout: post
title: "Jetic presents Train Short, Test Long: Attention with Linear Biases Enables Input Length Extrapolation"
root: ../../
---

At this week's lab meeting, Jetic will discuss the following work from ICLR '22: https://arxiv.org/pdf/2108.12409.pdf

**Abstract:** Since the introduction of the transformer model by Vaswani et al. (2017), a fundamental question has yet to be answered: how does a model achieve extrapolation at inference time for sequences that are longer than it saw during training? We first show that extrapolation can be enabled by simply changing the position representation method, though we find that current methods do not allow for efficient extrapolation. We therefore introduce a simpler and more efficient position method, Attention with Linear Biases (ALiBi). ALiBi does not add positional embeddings to word embeddings; instead, it biases query-key attention scores with a penalty that is proportional to their distance. We show that this method trains a 1.3 billion parameter model on input sequences of length 1024 that extrapolates to input sequences of length 2048, achieving the same perplexity as a sinusoidal position embedding model trained on inputs of length 2048 but training 11% faster and using 11% less memory. ALiBi's inductive bias towards recency also leads it to outperform multiple strong position methods on the WikiText-103 benchmark.

Wednesday, 31 May at 12pm

This will be a hybrid meeting at TASC1 9408. The zoom link will be posted on zulip.
