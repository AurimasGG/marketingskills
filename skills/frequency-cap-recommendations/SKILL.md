---
name: frequency-cap-recommendations
description: "Use when the user wants to find the optimal frequency cap for Meta campaigns, diagnose overexposure or audience saturation, identify where impressions are burning money past the conversion inflection point, or get frequency cap recommendations by campaign type. Trigger phrases: 'frequency too high,' 'overexposure,' 'audience saturated,' 'frequency cap,' 'too many impressions same people,' 'diminishing returns on frequency,' 'ad fatigue from frequency.'"
metadata:
  platform: Meta
  version: 1.0.0
---

# Frequency Cap Recommendations — Meta

## What it does
Analyzes frequency data across your Meta campaigns, identifies where you're overserving ads to the same people, and recommends frequency caps by campaign objective. Tells you the point where additional impressions stop driving conversions and start burning money.

## How it works
Correlate frequency levels with conversion rates, CTR, and CPA across campaigns. Find the inflection point for each campaign type — the frequency at which performance starts declining — and recommend caps that maximize reach and conversions while cutting waste from overexposure.

## What you need from the user
- Frequency data by campaign (average frequency, frequency distribution if available)
- CPA/CVR trend correlated with frequency changes
- Campaign objectives (awareness, traffic, conversions, retargeting)
- Current spend and time window (7-day, 30-day)

## Output format
1. **Current frequency distribution** — where each campaign sits vs optimal range
2. **Inflection point analysis** — the frequency at which CVR/CPA degrades, per campaign type
3. **Recommended caps** — specific frequency caps per campaign objective with time window
4. **Spend savings estimate** — how much budget gets freed up by capping overexposure
5. **Reallocation suggestion** — where to redirect the saved budget (fresh reach expansion)

## Practical example
Prospecting campaigns show conversion rate peaks at frequency 2.3 and drops 40% by frequency 4. Current average frequency is 5.1. Recommendation: frequency cap of 3 per 7 days for prospecting. Retargeting conversions continue up to frequency 6 before dropping — cap at 5 per 7 days. Estimated savings from capping: $3,400/month redirected to new reach.

## When to use it
- When CPMs rise and you suspect audience saturation
- Monthly frequency audits across all Meta campaigns
- When scaling spend and frequency climbs alongside budgets
- After creative refreshes to reset frequency baselines and set new caps
