---
layout: post
title: "Which Side Should We Scale? Revisiting Parameter Balance in Vision-Language Models (Ongoing)"
type: post
date: 2025-07-01
tags:
  - Vision-Language Models
  - Dual-Encoder Architecture
  - ViT
  - GPT-2
  - Model Efficiency
  - HuggingFace
  - Python
---
📂[GitHub Repository](https://yanyang-g0001.github.io/CSNLP_PROJECT/)

This project investigates the critical question of parameter allocation in dual-encoder vision-language models under limited budgets. We constructed a dual-tower architecture combining a pre-trained Vision Transformer (ViT) with a linear projection layer, and a text encoder based on averaged token embeddings from GPT-2. By systematically evaluating models with different scales of vision and language encoders, we found that maintaining a balanced parameter distribution between modalities is more important than the total parameter count  in our experimental setup. 
