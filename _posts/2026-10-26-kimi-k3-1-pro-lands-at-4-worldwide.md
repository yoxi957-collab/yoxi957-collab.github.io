---
layout: post
title: "Kimi K3.1 Pro Lands at #4 Worldwide: The Numbers, the Price Cut, and the Pushback"
date: 2026-10-26
tags: [kimi, open-weights, benchmarks, llm, news]
---

In the early hours of October 24 (Beijing time), Moonshot AI released **Kimi K3.1 Pro**. Within a day, the announcement passed 3 million views on X, the Hacker News thread climbed past 1,000 points with 600+ comments, and Chinese explainer videos on Bilibili were past 200k plays.

Why the attention? Because on paper it is **the closest an open-weights model has come to the top closed models.**

## Spec sheet

- Mixture-of-Experts, **2.8T total / 104B active** parameters
- **1M-token** context window
- Multimodal
- **Pro** and **Pro Highspeed** variants (Highspeed addresses K3's speed complaints)
- Open weights promised **before November 4**

Kimi is pitching two less common use cases: building complete projects in Unreal, Unity and Godot, and parametric 3D modeling in Blender and CAD software.

## The scoreboard

| Benchmark | K3.1 Pro | vs. K3 |
|---|---|---|
| Artificial Analysis Intelligence Index | 55, #4 globally | +11 |
| Terminal-Bench 4.0 | ~67%, highest of any model | K3: 13% |
| GDPval (real-world agentic work) | #3 globally | +312 |
| Arena WebDev | #8 | up 9 places |

A few notes:

- Only a handful of closed frontier models sit above it on Artificial Analysis. Once weights ship, it becomes the top-ranked open model there.
- Arena says its WebDev score **ties Claude Opus-5 at 70% lower cost**, and puts Kimi back among the top four labs on that board.
- An r/singularity thread about it overtaking Fable 5.1 drew 1,400+ upvotes, and some commenters argue open models now trail the best closed ones by roughly a month.

## Cheaper per token, too

| Per 1M tokens | K3.1 Pro | K3 |
|---|---|---|
| Input | $2 | $3 |
| Output | $10 | $15 |
| Cached input | $0.20 | $0.30 |

It is already live on OpenRouter and Vercel AI Gateway.

## The pushback

**1. Quotas burn fast.** The most common complaint. Some users say subscription quotas last 15–30 minutes; one HN commenter hit Kimi Code's 5-hour cap after $1.37 of usage. The cause: it reasons more, producing several times as many tokens per task as K3. Third-party estimates put total cost for the same workload roughly flat versus K3.

**2. A sponsorship controversy.** A Reddit post with 300+ upvotes alleges that Kimi asked overseas creators not to disclose paid promotions and supplied talking points. Kimi has not responded directly.

**3. Weaker writing.** Users on Zhihu and elsewhere say creative writing and roleplay regressed. Some flatly say K3 was better.

## My take

Leaderboards are getting easier to game, and a high rank doesn't mean the model is good at everything. But a jump from 13% to ~67% on Terminal-Bench and a top-four overall rank is hard to dismiss as benchmark tuning.

The real test comes when the weights drop before November 4 and anyone can deploy and evaluate it themselves.

*Sources: Kimi's official announcement, Artificial Analysis, Arena, Hacker News, Reddit r/singularity.*
