---
name: client-report-narratives
description: "Use when the user wants to write the executive summary or narrative section of a client performance report, turn raw campaign metrics into plain English explanation, or draft the 'what happened and why' section of a weekly/monthly report. Trigger phrases: 'write the report summary,' 'client report narrative,' 'explain these results,' 'turn this data into words,' 'write the executive summary,' 'what to say to client about performance,' 'report commentary,' 'monthly report write-up.'"
metadata:
  platform: Google and Meta
  version: 1.0.0
---

# Client Report Narratives — Google + Meta

## What it does
Takes your raw campaign performance data and writes the executive summary paragraph that goes at the top of the report. The plain English explanation of what happened, why it happened, and what's being done about it. The part every client actually reads.

## How it works
Take the key metrics for the period — spend, conversions, CPA, ROAS, CTR, and any notable changes — identify the most important trends, connect them to likely causes, and write a clear narrative that a non-technical stakeholder can understand without asking follow-up questions.

## What you need from the user
- Period dates (week, month, quarter)
- Key metrics: total spend, conversions, CPA, ROAS, CTR
- Comparison to previous period (% changes)
- Notable events: new creatives launched, budget changes, seasonality, platform changes
- Any issues or wins worth calling out
- Client tone preference (formal/professional vs direct and casual)

## Output format
1. **Executive summary paragraph** — 3-5 sentences covering what happened and the headline story
2. **Key wins** — specific numbers, not generic praise
3. **Problem areas** — flagged with context, not just red numbers
4. **Forward-looking recommendation** — 1-2 actions tied directly to the data
5. **Optional**: account-by-account breakdown if managing multiple campaigns

## Narrative structure to follow
- **Lede**: overall performance verdict (strong/on-track/under-pressure) with top-line numbers
- **Driver**: what caused the main movement (creative, audience, bid strategy, external)
- **Watch item**: one thing that needs attention next period with specific reason
- **Next step**: one concrete action being taken

## Practical example
Input: €45K spend, 1,180 leads at €38 CPA (down from €44), ROAS 4.2x, new UGC creative launched mid-month, Meta retargeting CPA up 18%.

Output narrative: "March delivered 1,180 leads at €38 CPA, a 14% improvement over February. The primary driver was the new UGC creative set launched mid-month, which outperformed static images 2.3x on Meta prospecting. Google Search held steady at €29 CPA with branded terms contributing 34% of volume. One area to watch: Meta retargeting CPA increased 18% as the audience pool shrinks — a lookalike refresh is scheduled for April to address this."

## Tone guidelines
- No jargon the client doesn't use ("CBO", "ASC+", "CPM" — translate or skip)
- Specific numbers over vague claims ("improved significantly" → "dropped 14%")
- Own the bad news — don't hide it, contextualize it
- One recommendation max per narrative — don't overwhelm

## When to use it
- Weekly and monthly client reporting
- Internal stakeholder updates
- QBR prep for multiple accounts
- Any time you need to turn a spreadsheet into a paragraph fast
