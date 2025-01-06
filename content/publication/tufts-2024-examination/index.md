---
title: An examination of ai-generated text detectors across multiple domains and models
authors:
- Brian Tufts
- Xuandong Zhao
- Lei Li
date: 2025-01-06
publishDate: '2024-12-15'
publication_types:
- paper-conference
publication: '*Neurips Safe Generative AI Workshop 2024*'
abstract: The proliferation of large language models has raised growing concerns about their misuse, particularly in cases where AI-generated text is falsely attributed to human authors. Machine-generated content detectors claim to effectively identify such text under various conditions and from any language model. This paper critically evaluates these claims by assessing several popular detectors (RADAR, Wild, T5Sentinel, Fast-DetectGPT, GPTID, LogRank) on a range of domains, datasets, and models that these detectors have not previously encountered. We employ various prompting strategies to simulate adversarial attacks, demonstrating that even moderate efforts can significantly evade detection. We emphasize the importance of the true positive rate at a specific false positive rate (TPR@FPR) metric and demonstrate that these detectors perform poorly in certain settings, with TPR@.01 as low as 0%. Our findings suggest that both trained and zero-shot detectors struggle to maintain high sensitivity while achieving a reasonable true positive rate.
tags:
- Large Language Models
- AI Evaluation
- AI Safety
links:
url_pdf: https://openreview.net/pdf?id=Pu41DTYo2f
url_code: 'https://github.com/LeiLiLab/llm-detector-eval'
---
