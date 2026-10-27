---
layout: post
title: "HKU Study: Chinese Video AI Leads on Looks, Trails on Safety — What Creators Should Do"
date: 2026-10-27
tags: [ai-video, seedance, hku, safety, generative-ai]
---

On October 26, 2026, the **HKU Business School Artificial Intelligence Evaluation Lab (AIEL)**, led by Professor Jack Jiang, released *Benchmarking the Performance and Safety of AI Video Generation Models*. The headline tension is simple: **Chinese models dominate visual quality; safety rankings tell a different story.**

## Why this study matters

In the first eight months of 2026, about **430,000 micro-dramas** were released in Chinese Mainland, and **AI-generated content accounted for more than 90%** of new releases. Video models are no longer a demo — they are an industrial production line.

## What was tested

Twelve models, via text-to-video and text+image-to-video, across six dimensions: visual continuity, physical plausibility, aesthetic quality, instruction alignment, audio quality, and audio-visual matching. Safety used prompts covering misinformation, illegal content, violence/explicit material, bias, and copyright.

**Models:** CogVideoX-3 (Zhipu), Hailuo-2.3 (MiniMax), Kling 3.0 & Kling O1 (Kuaishou), Pika 2.2, PixVerse V5.5, Seedance 1.5 Pro & Seedance 2.0 Pro (ByteDance), Sora 2 Pro (OpenAI), Veo 3.1 (Google DeepMind), Vidu Q3 Pro (ShengShu), Wan 2.6 (Alibaba).

## Overall visual quality (out of 5)

| Rank | Model | Visual | AV matching |
|---|---|---|---|
| 1 | Seedance 2.0 Pro | **3.84** (#1 all six dims) | 3.86 |
| 2 | Veo 3.1 | 3.47 | 3.51 |
| 3 | Vidu Q3 Pro | 3.44 | 3.49 |
| 4≈ | Kling 3.0 | 3.27 | 3.28 |
| 4≈ | Sora 2 Pro | 3.27 | 3.35 |
| 6 | Seedance 1.5 Pro | 3.25 | 3.37 |
| 7 | Wan 2.6 | 3.22 | 2.95 |
| 8 | Kling O1 | 3.04 | — |
| 9 | Hailuo-2.3 | 2.95 | — |
| 10 | CogVideoX-3 | 2.92 | — |
| 11 | PixVerse V5.5 | 2.82 | — |
| 12 | Pika 2.2 | 2.81 | — |

SCMP coverage echoed the same point: Chinese models beat US rivals on visual quality, with Seedance topping Veo and Sora.

## Safety overall (out of 5)

| Rank | Model | Safety |
|---|---|---|
| 1 | Hailuo-2.3 | **3.63** |
| 2 | Veo 3.1 | 3.62 |
| 3 | Pika 2.2 | 3.52 |
| 4 | PixVerse V5.5 | 3.48 |
| 5 | CogVideoX-3 | 3.35 |
| 6 | Seedance 2.0 Pro | **3.12** |
| 7 | Vidu Q3 Pro | 3.08 |
| 8 | Kling O1 | 2.50 |
| 9 | Kling 3.0 | 2.40 |
| 10 | Wan 2.6 | 2.32 |
| 11 | Seedance 1.5 Pro | 2.18 |

Sora was not included in the safety table — so there is no Sora safety score to cite here. Some models still produced inappropriate content on violence and illegal prompts.

## The key tension

- **Seedance 2.0 Pro:** #1 generation, #6 safety.
- **Hailuo-2.3:** #1 safety, roughly #9 on generation.

## Image references often hurt

Text+image inputs frequently scored worse than text-only. Example: Wan 2.6 text-to-video **3.41** vs text+image **2.75**. Do not assume a reference image improves the cut.

## What creators should do

1. **Chasing look:** Seedance 2.0 Pro leads this academic panel — but run your own safety review and human check.
2. **Regulated / brand / kids content:** prefer higher-safety models (Hailuo, Veo) even if looks are weaker.
3. **Don't assume image+text helps** — in this study it often hurt.
4. Industry is still quality-first; expect **safety to become the next competitive axis**.

Researchers recommend better A/V sync, better image+text understanding, longer coherent scenes, and stronger safety around misinfo, copyright, and ethics.

*Sources: HKU Business School / AIEL report, Professor Jack Jiang, SCMP coverage.*
