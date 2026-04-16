---
name: device-performance-split
description: "Use when the user wants to analyze performance differences between mobile, desktop, and tablet, diagnose why mobile CPA is higher than desktop, get device bid adjustment recommendations, or determine if campaigns should be split by device. Trigger phrases: 'device performance,' 'mobile vs desktop,' 'mobile CPA high,' 'device split,' 'desktop converts better,' 'mobile bid adjustment,' 'device breakdown,' 'tablet performance,' 'mobile landing page.'"
metadata:
  platform: Google and Meta
  version: 1.0.0
---

# Device Performance Split — Google + Meta

## What it does
Analyzes how your campaigns perform across mobile, desktop, and tablet. Identifies where device performance diverges significantly and recommends bid adjustments, campaign splits, or creative/landing page changes to capture the gap.

## How it works
Segment all campaign data by device type and compare CPA, CVR, CTR, and average order value. Identify campaigns where one device significantly outperforms or underperforms others, then determine whether the issue is ad-side (creative not working on mobile), landing-page-side (poor mobile experience), or audience-side (different intent by device).

## What you need from the user
- Performance data by device (export from Meta or Google with device segment applied)
- Key metrics: spend, clicks, conversions, CPA, CVR, CTR per device
- Current device bid adjustments (if any)
- Landing page context (mobile-optimized? load speed?)
- Campaign type (lead gen, ecommerce, app install, brand)

## Output format
1. **Device performance comparison** — CPA, CVR, CTR, spend share per device across all campaigns
2. **Gap identification** — campaigns with the largest device performance divergence
3. **Root cause analysis** — ad creative issue, landing page issue, or audience intent difference
4. **Bid adjustment recommendations** — specific % per device per campaign
5. **Campaign split candidates** — where devices need completely different strategies and budgets

## Practical example
B2B lead gen campaigns show desktop CPA at €41 / 3.8% CVR vs mobile CPA at €78 / 1.6% CVR. Mobile accounts for 58% of clicks. Deeper analysis shows landing page form has 9 fields (painful on mobile) and 4.2s load time on mobile vs 1.8s desktop. Recommendation: reduce mobile bids 25% until simplified 3-field mobile form and speed fix are live.

## When to use it
- When CPA is higher than expected and device splits haven't been checked
- After landing page redesigns to verify mobile experience
- When mobile traffic share increases but conversions don't follow
- For ecommerce accounts where mobile browsing vs desktop purchasing creates attribution gaps
