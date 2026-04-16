---
name: retargeting-window-analysis
description: "Use when the user wants to find the optimal retargeting window length for Meta audiences, analyze conversion lag data, determine if 30-day/14-day/7-day windows are right, or reduce wasted retargeting spend on users past their conversion window. Trigger phrases: 'retargeting window,' 'how long to retarget,' 'conversion lag,' 'retargeting audience too big,' 'retargeting CPA high,' 'stale retargeting,' '30-day window,' '7-day window.'"
metadata:
  platform: Meta
  version: 1.0.0
---

# Retargeting Window Analysis — Meta

## What it does
Analyzes your conversion lag data to determine the optimal retargeting window for each audience segment. Tells you whether your 30-day retargeting window should actually be 7 days, 14 days, or 60 days based on when people actually convert after their first visit.

## How it works
Look at time-to-conversion data across retargeting audiences — how many days between first site visit and conversion. Segment this by traffic source, product category, and audience type to find where most conversions happen and where retargeting spend stops producing returns.

## What you need from the user
- Conversion lag report or time-to-conversion data (from Meta Events Manager or GA4)
- Current retargeting window settings per campaign
- Retargeting CPA vs prospecting CPA
- Traffic source breakdown (Meta prospecting, Google Search, organic, email)
- Product category or AOV if relevant (high-consideration products have longer windows)

## Output format
1. **Conversion lag distribution** — % of conversions happening in each time window by source
2. **Optimal window per segment** — recommended days per traffic source and audience type
3. **Waste diagnosis** — spend in windows where conversions are negligible
4. **Restructure recommendations** — how to split retargeting campaigns by recency
5. **Bid adjustment logic** — higher bids for recent visitors, lower for older windows

## Practical example
Default retargeting window is 30 days for all audiences. Analysis shows 78% of conversions from Meta prospecting traffic happen within 7 days, only 4% after day 14. For Google Search traffic, 35% of conversions happen between days 14-30. Recommendation: 7-day high-bid window for Meta traffic, 14-day standard for search traffic, cut the 14-30 day window for Meta-sourced visitors — saving $1,900/month on users who weren't converting.

## When to use it
- When setting up retargeting campaigns for new accounts
- When retargeting CPA is creeping up and audience pools need tightening
- After significant changes in conversion funnel or product offering
- Quarterly to check if conversion behavior patterns have shifted
