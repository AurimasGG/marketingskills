---
name: geo-performance-analysis
description: "Use when the user wants to break down campaign performance by country, region, city, or DMA, identify which geos are wasting budget, find high-performing locations to increase spend in, or get geo bid adjustment recommendations. Trigger phrases: 'geo performance,' 'performance by location,' 'country breakdown,' 'regional performance,' 'which cities perform best,' 'geo bid adjustments,' 'location targeting,' 'where should we focus budget,' 'underperforming regions.'"
metadata:
  platform: Google and Meta
  version: 1.0.0
---

# Geo Performance Analysis — Google + Meta

## What it does
Breaks down campaign performance by geographic location at whatever level matters — country, state, city, DMA, zip code. Flags underperforming geos quietly eating budget and high-performing ones that deserve more spend. Recommends geo bid adjustments or campaign splits.

## How it works
Analyze performance data segmented by location, identify statistically significant performance differences (not just noise from low-volume areas), and calculate the cost of running campaigns in underperforming regions vs the conversions you'd lose by excluding or reducing them.

## What you need from the user
- Performance data segmented by geo (export from Meta Ads Manager or Google Ads geographic report)
- Key metrics: spend, conversions, CPA, ROAS, CVR by location
- Current geo targeting setup (inclusions, exclusions, bid adjustments)
- Campaign objective and funnel stage
- Minimum volume threshold for statistical significance consideration

## Output format
1. **Geo performance tier ranking** — top performers, average, underperformers with clear thresholds
2. **Waste diagnosis** — spend in underperforming geos with conversion cost
3. **Bid adjustment recommendations** — specific % adjustments per geo tier
4. **Campaign split candidates** — geos with enough volume to deserve independent campaigns
5. **Spend reallocation model** — what happens to total conversions if you shift budget from weak to strong geos

## Practical example
National campaigns spending evenly across all regions. Analysis finds 8 regions produce 65% of conversions at $24 CPA, while 12 regions spend €8,400/month at $71 CPA with minimal volume. Three cities outperform their regional averages by 40%+. Recommendation: reduce bids 40% in underperforming regions, +25% in top 8, create separate campaigns for the 3 outperforming cities.

## When to use it
- When running multi-market campaigns and need to optimize allocation
- After expanding into new regions to evaluate early performance
- Quarterly to catch geo performance shifts as market conditions change
- When clients ask "where should we focus" and you need data behind the recommendation
