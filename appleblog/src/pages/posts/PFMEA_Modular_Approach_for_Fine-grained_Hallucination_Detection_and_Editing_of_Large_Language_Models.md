---
layout: '../../layouts/MarkdownPost.astro'
title: 'PFME: A Modular Approach for Fine-grained Hallucination Detection and Editing of Large Language Models'
pubDate: 2024-07-09 04:42:18
description: ''
author: 'wanghaisheng'
cover:
    url: 'https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg'
    square: 'https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg'
    alt: 'cover'
tags: ['all search terms'] 
theme: 'light'
featured: true

meta:
 - name: author
   content: Kunquan Deng et.al.
 - name: keywords
   content: key3, key4

keywords: key1, key2, key3
---

## paper id
2407.00488v1
## download
[2407.00488v1](http://arxiv.org/abs/2407.00488v1)
## abstracts:
Large Language Models (LLMs) excel in fluency but risk producing inaccurate content, called "hallucinations." This paper outlines a standardized process for categorizing fine-grained hallucination types and proposes an innovative framework--the Progressive Fine-grained Model Editor (PFME)--specifically designed to detect and correct fine-grained hallucinations in LLMs. PFME consists of two collaborative modules: the Real-time Fact Retrieval Module and the Fine-grained Hallucination Detection and Editing Module. The former identifies key entities in the document and retrieves the latest factual evidence from credible sources. The latter further segments the document into sentence-level text and, based on relevant evidence and previously edited context, identifies, locates, and edits each sentence's hallucination type. Experimental results on FavaBench and FActScore demonstrate that PFME outperforms existing methods in fine-grained hallucination detection tasks. Particularly, when using the Llama3-8B-Instruct model, PFME's performance in fine-grained hallucination detection with external knowledge assistance improves by 8.7 percentage points (pp) compared to ChatGPT. In editing tasks, PFME further enhances the FActScore of FActScore-Alpaca13B and FActScore-ChatGPT datasets, increasing by 16.2pp and 4.6pp, respectively.
## QA:
coming soon
