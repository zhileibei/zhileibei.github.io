---
title: "xTrimoPGLM: Unified 100B-Scale Pre-trained Transformer for Deciphering the Language of Protein"
collection: publications
category: manuscripts
permalink: /publication/2024-10-14-xTrimoPGLM
excerpt: 'We propose a 100-billion-parameter unified protein language model, xTrimoPGLM, optimizing both protein understanding and generation objectives simultaneously through an innovative pre-training framework, demonstrating State-Of-The-Art performance on 18 protein understanding benchmarks, and powerful <i>de novo</i> sequence generation abilities.'
date: 2024-10-14
venue: 'Nature Methods'
# slidesurl: 'http://zhileibei.github.io/files/slides2.pdf'
paperurl: 'https://arxiv.org/abs/2401.06199'
citation: 'Bo Chen*, Xingyi Cheng*, Pan Li, Yangli‐ao Geng, Jing Gong, Shen Li, Zhilei Bei, et al. (2024). &quot;xTrimoPGLM: Unified 100B‐ Scale Pre‐Trained Transformer for Deciphering the Language of Proteins.&quot; <i>Acceptance in Principle at Nature Methods, preprint at arXiv:2401.06199</i>.'
---

Protein language models have shown remarkable success in learning biological information from protein sequences. However, most existing models are limited by either autoencoding or autoregressive pre-training objectives, which makes them struggle to handle protein understanding and generation tasks concurrently. We propose a unified protein language model, xTrimoPGLM, to address these two types of tasks simultaneously through an innovative pre-training framework. Our key technical contribution is an exploration of the compatibility and the potential for joint optimization of the two types of objectives, which has led to a strategy for training xTrimoPGLM at an unprecedented scale of 100 billion parameters and 1 trillion training tokens. Our extensive experiments reveal that 1) xTrimoPGLM significantly outperforms other advanced baselines in 18 protein understanding benchmarks across four categories. The model also facilitates an atomic-resolution view of protein structures, leading to an advanced 3D structural prediction model that surpasses existing language model-based tools. 2) xTrimoPGLM not only can generate de novo protein sequences following the principles of natural ones, but also can perform programmable generation after supervised fine-tuning (SFT) on curated sequences. These results highlight the substantial capability and versatility of xTrimoPGLM in understanding and generating protein sequences, contributing to the evolving landscape of foundation models in protein science.
