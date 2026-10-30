---
layout: post
title: "Mistral Large 4 (Le Chonk) Open Weights: Specs, Benchmarks and What It Costs to Run"
date: 2026-10-30
tags: [ai-news, open-source, mistral, llm, self-hosting]
---

Mistral released the weights of Mistral Large 4, nicknamed Le Chonk, on October 29. The Hacker News thread went past a thousand points. These are my notes on what's in the release and how it compares, mostly for anyone thinking about self-hosting it.

## Specs

| Item | Value |
|---|---|
| Architecture | MoE, MLA + DeepSeek-style sparse attention (DSA) |
| Parameters | ~1T total, ~49B active |
| Context | 1M tokens |
| Input | Text and images |
| Official weights | FP8, NVFP4 (community GGUFs from Unsloth and llama.cpp) |
| Serving | vLLM, SGLang, llama.cpp, Transformers |
| License | Mistral Ecosystem Open-Weight License (modified MIT) |

The license allows free use, modification, fine-tuning and commercial products. Companies that offer the model itself as a hosted service need a separate commercial license.

## Hardware

According to SGLang's docs, as reported by The Decoder:

- Standard version: 8 × Nvidia B300
- Compressed version: 4 × Nvidia GB300

If you don't have that, it's available through Mistral's API, OpenRouter, Microsoft Foundry and NVIDIA NIM.

## Coding benchmarks

| Benchmark | Mistral Large 4 | Comparison |
|---|---|---|
| Terminal-Bench 4.0 | 41% (preview: 28%) | GLM-5.3: 40% |
| AA Coding Agent Index | 48% | GLM-5.3: ~48%, Claude Code + Opus 5.5: 62 |
| FrontierCode 2.0 | 19.7% | Claude Opus 5.5: 46% |
| Surge blind test vs Opus 5.5 | 22% win rate | — |

Mistral says it reaches its Coding Agent Index score with 47% fewer tokens per task than GLM-5.3.

## Overall and security

| Metric | Mistral Large 4 | Comparison |
|---|---|---|
| AA Intelligence Index v5 | 26 | DeepSeek V4.1 Flash: 32, GLM-5.3: 32 |
| AA Cyber Index | 51% | DeepSeek V4.1 Flash: 57%, MiMo-V2.6-Pro: 56% |
| Malicious cyber request refusal | 96.6% | Highest among open models (Mistral's figure) |

Mistral markets it as the leading open model for cyber defense, but by its own chart it's third on the Cyber Index.

## Price and speed

| Item | Value |
|---|---|
| API input / output | $0.70 / $2.10 per M tokens |
| Cached input | $0.07 per M tokens |
| Output speed | 161 tokens/s (Artificial Analysis) |
| Avg cost per AA index task | $2.06 (GLM-5.3: $5.01, DeepSeek V4.1 Flash: $0.60) |

## My notes

- For coding agents it's a real option among open models, roughly level with GLM-5.3 and cheaper on tokens.
- For general use on a budget, DeepSeek V4.1 Flash still scores higher at a fraction of the cost.
- Its strongest selling point is that it's trained in Europe and can be self-hosted and audited. That matters a lot for regulated European companies and much less for everyone else.
- Kimi K3.1 Pro's weights are reportedly due by November 4, so the open-model rankings may shift soon.

*Sources: Mistral's announcement, the Hugging Face blog, The Decoder, Artificial Analysis, Hacker News.*
