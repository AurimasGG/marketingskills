---
name: performance-benchmarking
description: "Use when the user wants to compare their campaign metrics against industry benchmarks, answer 'is our CPA good?', contextualize performance for a client or stakeholder, or find where they're ahead or behind vertical averages. Trigger phrases: 'benchmark our performance,' 'is this CPA good,' 'industry benchmarks,' 'how do we compare,' 'average CPA for our industry,' 'benchmark CTR,' 'are we above average,' 'compare to competitors,' 'vertical benchmarks,' 'what is a good ROAS for.'"
metadata:
  platform: Google and Meta
  version: 1.0.0
---

# Performance Benchmarking — Google + Meta

## What it does
Compares your key metrics against industry benchmarks for your specific vertical, campaign type, and platform. Tells you where you're ahead, where you're behind, and where there's room to improve — adjusted for account size and spend level, because a €10K/month account and a €500K/month account have different benchmark realities.

## How it works
Take core metrics (CPC, CTR, CVR, CPA, ROAS, CPM, hook rate) and compare them against available benchmark data for your industry and campaign type. Adjust for factors that affect comparison — account maturity, geo market, budget level, funnel stage — so you're not comparing your prospecting CPA against someone else's retargeting CPA.

## What you need from the user
- Your current key metrics (CPA, ROAS, CTR, CVR, CPM, CPC)
- Industry/vertical (ecommerce, SaaS, lead gen, health, finance, etc.)
- Platform (Meta, Google Search, Google PMax, both)
- Campaign type (prospecting, retargeting, branded search, non-branded)
- Monthly spend level (affects what "good" looks like)
- Geo market (US, EU, UK benchmarks differ)

## Output format
1. **Metric-by-metric comparison** — your number vs benchmark, % variance, above/below
2. **Outperformance breakdown** — where you're ahead and likely why
3. **Underperformance breakdown** — where you're behind with likely root cause
4. **Prioritized improvement opportunities** — ranked by potential impact if closed to benchmark
5. **Benchmark context** — what "good" means for your specific situation, not just raw averages

## Benchmark context to always include
- Benchmarks vary significantly by vertical, geo, and spend level
- Prospecting CPA is always higher than retargeting CPA — compare like-for-like
- Meta CPMs in EU are typically 30-50% lower than US
- B2B lead gen CTRs are lower than ecommerce by nature — not a failure
- New accounts have higher CPAs than mature ones — maturity context matters

## Practical example
SaaS client Google Search: 3.2% CTR and €52 CPA. CTR is 18% above B2B SaaS benchmark (strong ad relevance), but CPA is 30% above benchmark — gap is in CVR (2.1% vs 3.4% benchmark). This points to landing page, not ads. On Meta: CPM at benchmark, but video hook rate 22% vs 35% benchmark — first 3 seconds of video ads need work.

## When to use it
- When pitching new clients to identify quick wins in their accounts
- QBRs and annual reviews to show performance in context
- When clients ask "is our CPA good?" and need a data-backed answer
- For internal team benchmarking across multiple client accounts in the same vertical
