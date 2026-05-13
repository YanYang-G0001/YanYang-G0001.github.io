---
layout: post
title: "Which Side Should We Scale? Revisiting Parameter Balance in Vision-Language Models"
type: post
date: 2025-06-01
tags:
  - Vision-Language Models
  - Dual-Encoder Architecture
  - Model Scaling
  - Representation Learning
  - ViT
  - GPT-2
  - PyTorch
  - HuggingFace
---
📂[GitHub Repository](https://yanyang-g0001.github.io/CSNLP_PROJECT/)

This project investigates the critical question of parameter allocation in dual-encoder vision-language models under limited budgets. We constructed a dual-tower architecture combining a pre-trained Vision Transformer (ViT) with a linear projection layer, and a text encoder based on averaged token embeddings from GPT-2. By systematically evaluating models with different scales of vision and language encoders, we found that maintaining a balanced parameter distribution between modalities is more important than the total parameter count  in our experimental setup. 

### Contributions:
- Conducted a literature review on vision-language dual-encoder architectures  
- Designed and implemented a series of dual-tower models with varying vision-text parameter allocations  
- Performed systematic experiments and analyzed the impact of modality balance on model performance