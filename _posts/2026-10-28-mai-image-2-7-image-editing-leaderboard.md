---
layout: post
title: "Microsoft's MAI Image 2.7 Is #2 in AI Image Editing. Here's Why That Ranking Is Closer Than It Looks"
date: 2026-10-28
tags: [image-editing, microsoft, mai-image, gpt-image, leaderboards]
---

On October 27, 2026, Microsoft AI announced **MAI Image 2.7**, an image editing model launching in preview. Microsoft's headline: **No. 2 on Artificial Analysis's image editing leaderboard**, ahead of OpenAI's GPT Image 2.5 Flare, and **No. 3 on Arena's Image Edit leaderboard**, which Microsoft says makes it the No. 2 lab there.

Those rankings are real. They are also tighter, and less final, than the headline suggests. Here is how to read them, and what to actually use today.

## TL;DR

| If you need... | Recommendation |
|---|---|
| The best editing quality available by API today | GPT Image 2.5 Sunburst still leads both boards |
| Strong quality at a much lower price | Nano Banana 2.1 or MAI-Image-2.6 |
| Scene restyling, relighting, text edits | MAI Image 2.7 is worth testing once you can access it |

## The Artificial Analysis board (AA-Image-Editing v2.1)

| Rank | Model | Elo | Samples | API price per 1k images |
|---|---|---|---|---|
| 1 | GPT Image 2.5 Sunburst (max) | 1199 ±11 | 18,250 | $210.7 |
| 2 | **MAI-Image-2.7-Preview** | **1193 ±15** | 4,891 | no API listed |
| 3 | GPT Image 2.5 Flare (max) | 1182 ±11 | 19,136 | $210.7 |
| 4–6 | MAI-Image-2.6 | 1151 | 16,644 | $38.9 |
| 4–6 | Krea 3 (Ultra) | 1151 | 5,505 | $270.0 |
| 4–6 | Nano Banana 2.1 | 1151 | 6,868 | $33.6 |
| 9 | Seedream 5.0 Pro | 1131 | 13,380 | $90.0 |
| 10 | Muse Image | 1129 | 13,358 | $10.0 |

## The Arena board (Image Edit)

| Rank | Model | Score | Votes |
|---|---|---|---|
| 1 | GPT-Image-2.5 Sunburst | 1517 ±5 | 90,545 |
| 2 | GPT-Image-2.5 Flare | 1482 ±5 | 87,941 |
| 3 | **MAI-Image-2.7-Preview** | **1471 ±10** | 3,402 |
| 4 | GPT-Image-2 (Medium) | 1460 ±3 | 336,785 |
| 5 | Grok Imagine Image 2.0 | 1439 ±6 | 32,951 |
| 7 | Gemini Nano Banana 2.1 | 1427 ±6 | 12,956 |

## What Microsoft says improved

- Better than MAI-Image-2.6 across **all 10 use cases and all 7 editing actions** Artificial Analysis evaluates.
- At the category frontier in **enhancement and restoration, reasoning-based edits, scene and style, and text or symbol editing**.
- Biggest lead in **scene and style**, about **24 Elo ahead** of the next-best model.

## Why the ranking is closer than it looks

1. **Overlapping error bars.** On Artificial Analysis, 1193 ±15 vs 1199 ±11 is statistically a tie with the leader; its rank range is listed as 1 to 3.
2. **Small sample.** 4,891 comparisons vs more than 18,000 for both GPT Image 2.5 variants; on Arena, 3,402 votes vs about 90,000. Preview scores tend to move.
3. **No API price yet.** You can't compare cost per image, which for most teams is half the decision.
4. **On Arena, OpenAI still leads clearly.** Sunburst is 46 points ahead.

## What I'd do

- **Need top quality now:** GPT Image 2.5 Sunburst, at roughly $0.21 per image on Artificial Analysis's pricing.
- **Need volume:** Nano Banana 2.1 ($33.6 per 1k) or MAI-Image-2.6 ($38.9 per 1k) sit only about 40–50 Elo behind at a fraction of the price.
- **Watch MAI Image 2.7** for restyling and text edits, and re-check the boards in a couple of weeks once the sample size grows.

*Sources: Microsoft AI's October 27 announcement, the Artificial Analysis AA-Image-Editing v2.1 leaderboard, and Arena's Image Edit leaderboard.*
