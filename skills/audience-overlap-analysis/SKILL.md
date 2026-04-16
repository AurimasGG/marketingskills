---
name: audience-overlap-analysis
description: "Use when the user wants to find audience cannibalization on Meta, check if ad sets are competing against each other in auction, diagnose CPM inflation from overlapping targeting, or get consolidation/exclusion recommendations. Trigger phrases: 'audience overlap,' 'ad sets competing,' 'CPM inflated,' 'cannibalizing each other,' 'overlapping audiences,' 'internal auction competition,' 'consolidate ad sets,' 'too many ad sets.'"
metadata:
  platform: Meta
  version: 1.0.0
---

# Audience Overlap Analysis — Meta

## What it does
Compares your Meta ad sets and identifies where audiences overlap significantly, causing your ads to compete against each other in the same auctions. Tells you exactly which ad sets are cannibalizing each other and how much it's costing you in inflated CPMs.

## How it works
Analyze ad set targeting parameters — custom audiences, lookalikes, interest stacks, age/gender splits, and geo targeting — and map the overlap between them. Cross-reference with delivery data to identify where auction overlap is actually driving up costs vs where it's theoretical but not impactful.

## What you need from the user
- Ad set names and targeting parameters (interests, custom audiences, lookalikes, geo, age/gender)
- Current CPMs per ad set
- Spend and conversion volume per ad set for the period
- Account structure context (CBO vs ABO, campaign objectives)

## Output format
1. **Overlap map** — which ad sets share significant audience pools, estimated overlap %
2. **CPM inflation diagnosis** — which overlaps are causing actual cost increases
3. **Consolidation recommendations** — specific ad sets to merge, with rationale
4. **Exclusion strategy** — which audience exclusions to apply if keeping separate ad sets
5. **Projected impact** — estimated CPM reduction from recommended changes

## Practical example
Running 6 prospecting ad sets with different interest stacks. Ad sets 2, 4, and 6 have estimated 60%+ audience overlap because the interest categories share the same underlying user pool. These three ad sets have CPMs 28% higher than the non-overlapping ones. Recommendation: consolidate into one broad ad set and let Meta's algorithm optimize, or apply cross-exclusions.

## When to use it
- When scaling Meta campaigns and adding new ad sets
- If CPMs are rising without clear external cause
- During account restructuring to clean up legacy targeting
- When frequency is high across multiple ad sets targeting similar people
