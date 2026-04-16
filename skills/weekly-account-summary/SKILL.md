---
name: weekly-account-summary
description: "Use when the user wants a structured weekly summary of what happened across their ad accounts, needs a Monday morning briefing format, wants to identify top issues and wins for the week, or needs to write a weekly status update for a team or client. Trigger phrases: 'weekly summary,' 'week in review,' 'account summary,' 'what happened this week,' 'weekly briefing,' 'weekly report,' 'Monday morning summary,' 'week recap,' 'performance summary this week,' 'weekly account review.'"
metadata:
  platform: Google and Meta
  version: 1.0.0
---

# Weekly Account Summary — Google + Meta

## What it does
Generates a plain English summary of everything that happened across your accounts this week. What improved, what declined, what needs immediate attention, and what to prioritize next week. The Monday morning briefing that saves you an hour of pulling reports and context-switching between platforms.

## How it works
Process weekly performance data across Google and Meta, compare to previous week and trailing 4-week average, identify the most meaningful changes (not just any change, but changes that matter financially), and write a structured briefing — fires first, wins second, housekeeping third.

## What you need from the user
- Weekly performance data for all active campaigns (spend, conversions, CPA, ROAS)
- Week-over-week comparison (% changes)
- Any changes made during the week (new creatives, budget shifts, audience changes, bid strategy changes)
- Account count (single account or multiple clients)
- Any external context (seasonality, promotions, product launches)

## Output format

### Single account
1. **Headline** — one sentence verdict on the week (on pace / strong / needs attention)
2. **Top 3 issues** — ranked by urgency with specific cause and recommended action
3. **Top wins** — what's working and whether it's scalable
4. **Week vs previous week vs 4-week average** — spend, conversions, CPA
5. **Priority action list** — specific tasks for the coming week

### Multi-account (agency)
Same structure, but with a cross-account overview first, then account-by-account breakdown. Flags which accounts need attention vs which are running fine.

## Summary structure to follow
- **Status line**: total spend (vs pace), total conversions, blended CPA
- **Fire #1**: most urgent issue + one-line cause + one-line fix
- **Fire #2**: second most urgent (if exists)
- **Win**: best performing element worth noting or scaling
- **Next week**: 2-3 specific actions with owner/deadline if relevant

## Practical example
"Week of March 10 — Total spend €41,200 (on pace). Three things to know:

(1) Meta prospecting CPA jumped 22% to €46, driven by creative fatigue on UGC set running 4 weeks — rotate in new testimonial variants by Wednesday.

(2) Google Search branded CPC dropped 15% — competitor appears to have pulled back on brand bidding, no action needed, monitor next week.

(3) PMax added 23 new converting search terms this week, 4 are high-intent worth adding as exact match in dedicated campaigns.

Win: new carousel ad set delivering €28 CPA at 2.1x ROAS after 5 days — scaling opportunity if it holds through next week."

## When to use it
- Every Monday before opening the accounts
- For agencies managing multiple accounts who need a fast cross-client overview
- Client-facing weekly updates that need to be written quickly
- End of week wrap-ups for team handoffs or status reports
