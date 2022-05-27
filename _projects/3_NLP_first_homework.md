---
layout: page
title: NER
description: Named Entity Recognition
img: assets/img/NLP/named_entity_recognition.jpg
importance: 1
category: work
---

<h1>Overview</h1>
<a href="https://github.com/ColdFrenzy/nlp2022-hw1">code</a>

Named Entity Recognition is the task of locating and classifying named entities mentioned in text.

In this project we were provided with a dataset and we were not allowed to use contextualized word embeddings (ELMo, etc.) and transformers-based (BERT, BART, RoBERTa, etc.) architectures.

My proposed solution made use of the "glove-wiki-gigaword-5" pre-trained word embedding and a Bidirectional long-short term memory (BiLSTM) architecture with a custom random field (CRF) on top.

