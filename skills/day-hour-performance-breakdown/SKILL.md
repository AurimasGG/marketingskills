---
name: day-hour-performance-breakdown
description: "Use when the user wants to analyze performance by day of week or hour of day, find the best and worst times to run ads, get ad schedule recommendations, or identify time-based budget waste. Trigger phrases: 'day parting,' 'hour of day performance,' 'day of week breakdown,' 'ad schedule,' 'when do ads perform best,' 'time of day analysis,' 'dayparting recommendations,' 'what hours to run ads,' 'weekend vs weekday performance,' 'best time to advertise.'"
metadata:
  platform: Google and Meta
  version: 1.0.0
---

# Day/Hour Performance Breakdown — Google + Meta

## What it does
Analyzes performance by day of week and hour of day across your campaigns. Identifies when your ads perform best and worst, recommends ad schedule adjustments with estimated savings, and tells you exactly what you'd give up by restricting hours.

## How it works
Segment performance data by day and hour, looking at CPA, CVR, CTR, and spend distribution. Identify statistically meaningful patterns (not just noise from low-volume hours) and calculate the cost of running ads during underperforming windows vs the conversions you'd lose by turning them off.

## What you need from the user
- Performance data segmented by hour and day (export from Meta Ads Manager: Breakdown → Time → Hour of day / Day of week, or Google Ads: Dimensions → Time)
- Key metrics: spend, conversions, CPA, CVR per time segment
- Campaign type (B2B lead gen, ecommerce, app, branding — patterns differ significantly)
- Current ad schedule settings (running 24/7? any existing restrictions?)
- Monthly budget to contextualize reallocation impact

## Output format
1. **Performance heatmap** — CPA/CVR by day and hour, flagging high and low performers
2. **Statistical confidence** — which time segments have enough volume to trust
3. **Schedule recommendations** — exact hours and days to adjust with rationale
4. **Financial impact model** — spend saved, conversions lost, net effect of reallocation to peak hours
5. **Per-campaign-type breakdown** — brand, prospecting, retargeting often have different patterns

## Practical example
B2B SaaS campaigns show CPA of €31 during weekday business hours (8am-6pm) but €67 on weekends and €54 after 9pm. Weekend spend is €4,200/month producing 63 leads at €67 each. Cutting weekends and nights saves €6,100/month while losing only 89 conversions — reallocating that budget to peak hours generates an estimated 142 conversions at the lower CPA. Net gain: 53 additional conversions at same total spend.

## When to use it
- When setting up ad schedules for new campaigns
- Quarterly reviews to adjust schedules as behavior patterns shift
- When budgets are tight and need to maximize efficiency
- For B2B accounts where business hours vs off-hours performance differs significantly
- For ecommerce accounts to catch weekend/evening purchase spikes worth capitalizing on
