---
layout: post
title: "A Hybrid Approach for Detecting AI-Generated Text in English"
type: post
date: 2026-01-01
tags:
  - code available
  - NLP
  - DeBERTa-v3-base
  - DNA-DetectLLM
  - HuggingFace
  - PyTorch
  - Python
---
📂[GitHub Repository](https://github.com/YanYang-G0001/A_Hybrid_Approach_for_Detecting_AI_Generated_Text_in_English)

This project addresses the challenge of distinguishing between AI-generated and human-written English text. We proposed a hybrid detection model that combines the strengths of train-based discriminative classifiers (DeBERTa) and train-free statistical methods (DNA-DetectLLM) to improve detection robustness and performance across diverse domains and generation models.

### Contributions:

- Conducted literature review and reproduced key baseline methods  
- Designed and implemented the full experimental pipeline  
- Integrated DeBERTa-v3-base classifier with DNA-DetectLLM statistical signals into a unified hybrid framework  
- Built data processing, training, and evaluation pipelines 
- Ran experiments, performed result analysis and error analysis

### References

This project builds upon the following works:
- [DNA-DetectLLM: a train-free statistical detection method (Xiaoweizhu et al.)](https://github.com/Xiaoweizhu57/DNA-DetectLLM)
- [Advacheck at GenAI Detection Task 1: AI Detection Powered by Domain-Aware Multi-Tasking (Gritsai et al.)](https://github.com/Advacheck-OU/ai-detector-coling2025)  
- COLING 2025 GenAI Content Detection Task