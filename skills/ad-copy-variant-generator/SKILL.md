---
name: ad-copy-variant-generator
description: "Use when the user wants to generate new ad copy variants based on top-performing ads, create meaningful creative variations for testing, write RSA headlines and descriptions, or iterate on existing copy angles without starting from scratch. Trigger phrases: 'ad copy variants,' 'new creative variations,' 'iterate on this ad,' 'generate ad copy,' 'RSA headlines,' 'copy testing,' 'creative refresh,' 'write ads based on winners,' 'what to test next in copy.'"
metadata:
  platform: Google and Meta
  version: 1.0.0
---

# Ad Copy Variant Generator — Google + Meta

## What it does
Analyzes your top performing ads, identifies what's working in the hooks, CTAs, messaging angles, and formats, then generates new variants that follow the same winning patterns while introducing enough variation to test meaningfully.

## How it works
Ingest ad performance data alongside actual ad copy and creative specs. Correlate performance metrics (CTR, CVR, CPA) with copy elements — headline structure, primary text length, tone, CTA type, pain point vs benefit framing, social proof usage. Generate variants that preserve winning elements while changing specific variables.

## What you need from the user
- Top performing ad copy (headlines, primary text, CTAs) with performance metrics
- Platform and format (Meta feed, Stories, Google RSA, PMax)
- Product/offer details and unique selling points
- Target audience and their primary pain points
- Character limits if platform-specific (Google RSA: 30-char headlines, 90-char descriptions)

## Output format
1. **Winning pattern analysis** — what elements in top performers are driving results
2. **Variant sets** — grouped by what's being tested (hook style, CTA, angle, social proof)
3. **Test annotations** — which winning element each variant preserves vs what's changing
4. **Test priority** — which variable has most variance in your data and should be tested first
5. **A/B pairing recommendations** — which variants to run against each other

## Practical example
Best performing Meta ad leads with a specific number ("Cut onboarding from 3 weeks to 3 days"), uses a customer quote in the middle, soft CTA at end. Claude generates 8 variants: 4 keep the number-led hook but change the metric, 2 test question-based hooks with same body structure, 2 flip to benefit-first with the number as proof. Each variant changes one or two elements to isolate what's driving performance.

## When to use it
- When top creatives start fatiguing and you need fresh variants fast
- Creative brainstorms where you need a starting point, not a blank page
- When scaling to new audiences that might respond to different angles
- RSA headline generation where you need 15 headlines that aren't repetitive
