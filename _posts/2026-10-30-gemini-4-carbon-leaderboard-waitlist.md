---
layout: post
title: "Gemini 4 Carbon: #1 on the Leaderboard, Locked Behind a Waitlist"
date: 2026-10-30
tags: [ai-news, google-gemini, cybersecurity, benchmarks]
---

Google announced Gemini 4 Carbon on October 28, two weeks after Gemini 4 Argon. It's now the top-scoring model on the Artificial Analysis Intelligence Index v5.0. It's also not available to developers. Here's what the published numbers actually say.

## The headline score

| Model | AA Intelligence Index v5.0 |
|---|---|
| Gemini 4 Carbon | 59 |
| Claude Opus 5.5 | 58 |
| GPT-6 Astra | 57 |
| Gemini 4 Argon | 50 |

One point is not a big lead. I'd treat the top three as roughly tied overall.

## Where it wins and where it doesn't

From the comparison table on the Google DeepMind model page:

| Benchmark | What it tests | Carbon | Best rival |
|---|---|---|---|
| Terminal-Bench 4.0 (AA) | Terminal tasks | 65.2% | Opus 5.5, 59.6% |
| FrontierSWE 2 | Agentic coding | 61.2% | GPT-6 Astra, 65.5% |
| OSWorld-2.1 | Computer use | 81.5% | Opus 5.5, 87.2% |
| GraphWalks (256k–1M) | Long context | 96.2% | Argon, 84.2% |
| SEC-bench Pro | Finding vulnerabilities | 88.2% | GPT-6 Astra, 85.4% |
| ExploitGym | Exploitation | 54.8% | GPT-6 Astra, 42.4% |
| CWE-bench | Patching | 71.0% | Argon / Astra, 68.0% |

The pattern is pretty clear. Big wins on long context and security, losses on computer use and one of the coding benchmarks.

## Why there's no API access

Google says the security results were measured without guardrails. The ExploitGym number is the one to watch: a twelve-point lead in turning bugs into working exploits is useful for red teams and dangerous everywhere else.

So the rollout goes in stages:

1. A subset of cyber defenders, starting this week.
2. More trusted partners through the Fairwind Program (over 650 organizations, according to SecurityWeek and Google DeepMind).
3. Developers, businesses and consumers, with no date given.

Google also says it's taking part in the US government's voluntary pre-release testing.

Pricing is already public: $2 per million input tokens, $10 per million output, and cached input 95% cheaper. That matches Argon.

## My notes

- If you're picking a model for a coding agent this week, nothing changed. Carbon isn't clearly better than Opus 5.5 or Astra there anyway.
- If you run security scans, it's worth building the pipeline now so that switching models later is a config change.
- Leaderboards should mark models that aren't publicly callable. A top spot you can't use doesn't help anyone choose.

*Sources: Google blog, Google DeepMind model page, Artificial Analysis, The Verge, SecurityWeek.*
