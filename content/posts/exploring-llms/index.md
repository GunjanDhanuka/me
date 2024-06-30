+++
title = 'LLMs Blog'
date = 2024-05-20T01:32:42+05:30
draft = true
math = true
+++

Let us first start from the beginning of language models.

## Neural Machine Translation by Jointly Learning to Align and Translate (2014) 
[Paper](https://arxiv.org/abs/1409.0473)

- Each time the proposed model generates a word in a translation, it (soft-) searches for a set of positions in a source sentence where the most relevant information is concentrated (motivation for *attention*). The model then predicts a target word using the context vectors with these source positions and previously generated target words.
- Does **not** attempt to encode whole input sentence to a single fixed-length vector. This makes it better for long sentences compared to encoder-decoder models.
