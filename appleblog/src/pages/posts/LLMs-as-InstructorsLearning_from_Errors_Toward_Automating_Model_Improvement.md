---
layout: '../../layouts/MarkdownPost.astro'
title: 'LLMs-as-Instructors: Learning from Errors Toward Automating Model Improvement'
pubDate: 2024-07-09 04:42:17
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
   content: Jiahao Ying et.al.
 - name: keywords
   content: key3, key4

keywords: key1, key2, key3
---

## paper id
2407.00497v1
## download
[2407.00497v1](http://arxiv.org/abs/2407.00497v1)
## abstracts:
This paper introduces the innovative "LLMs-as-Instructors" framework, which leverages the advanced Large Language Models (LLMs) to autonomously enhance the training of smaller target models. Inspired by the theory of "Learning from Errors", this framework employs an instructor LLM to meticulously analyze the specific errors within a target model, facilitating targeted and efficient training cycles. Within this framework, we implement two strategies: "Learning from Error," which focuses solely on incorrect responses to tailor training data, and "Learning from Error by Contrast", which uses contrastive learning to analyze both correct and incorrect responses for a deeper understanding of errors.   Our empirical studies, conducted with several open-source models, demonstrate significant improvements across multiple benchmarks, including mathematical reasoning, coding abilities, and factual knowledge. Notably, the refined Llama-3-8b-Instruction has outperformed ChatGPT, illustrating the effectiveness of our approach. By leveraging the strengths of both strategies, we have attained a more balanced performance improvement on both in-domain and out-of-domain benchmarks. Our code can be found at https://yingjiahao14.github.io/LLMs-as-Instructors-pages/.
## QA:
coming soon
