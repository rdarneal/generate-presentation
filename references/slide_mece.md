# MECE Decomposition Slide Pattern (Pattern D)

> **Note:** The `---` dividers in this file are documentation section boundaries. When generating presentation output, use `---` only as slide boundary markers per SKILL.md format rules.

## Pattern Overview

**Designation:** Pattern D (Layer 2 -- Slide-Level Pattern)
**Concept:** Break a complex topic into mutually exclusive, collectively exhaustive categories on a single slide.
**Origin:** McKinsey & Company structuring principle, foundational to management consulting methodology.
**Best For:** Issue structuring, revenue/cost breakdowns, market segmentation, strategic option analysis, argument organization.

**When to Use:**
- You need to break a whole into its parts (revenue, cost, market, organization, time, etc.)
- The audience must see your analysis covers everything and double-counts nothing
- You are presenting drivers, root causes, segments, or categories that together explain a phenomenon
- You need to show relative magnitude of each component (quantified decomposition)
- You are structuring the supporting arguments for a Pyramid Principle deck

**When NOT to Use:**
- The topic is naturally sequential or chronological (use a timeline or process flow)
- You have a simple list of unrelated items (a bullet list suffices)
- The components are inherently overlapping and cannot be cleanly separated
- You only have one or two components (decomposition adds no value)

---

## Core Philosophy

**"No overlaps, no gaps."**

MECE is the foundation of structured thinking. When you decompose a problem into MECE buckets, you guarantee two things:

1. **Nothing is double-counted** (Mutually Exclusive) -- each item belongs to exactly one category.
2. **Nothing is missed** (Collectively Exhaustive) -- the categories together cover the entire space.

Executives evaluate the rigor of your thinking before they evaluate your conclusions. A decomposition with overlapping categories signals sloppy analysis. A decomposition that misses a major category invites the most damaging question in a boardroom: "What about...?"

When categories overlap, quantification breaks down -- you cannot add costs without double-counting. MECE is not just an aesthetic preference; it is a mathematical requirement for any decomposition where the parts must equal the whole.

---

## Visual Layout Diagrams

### Layout 1: Tree / Hierarchy (Primary)

```
+---------------------------------------------------------+
| Title: "Revenue growth driven by three distinct levers"  |
+---------------------------------------------------------+
|                                                          |
|                  +-------------+                         |
|                  |   Revenue   |                         |
|                  |   Growth    |                         |
|                  |   (+12%)    |                         |
|                  +------+------+                         |
|            +------------+------------+                   |
|            v            v            v                   |
|     +----------+  +----------+  +----------+            |
|     |  Price   |  |  Volume  |  |   Mix    |            |
|     |  (+5%)   |  |  (+4%)   |  |  (+3%)   |            |
|     +----------+  +----------+  +----------+            |
|                                                          |
|  Price: Premium repositioning drove 5% ASP increase     |
|  Volume: New channel partnerships added 4% unit growth  |
|  Mix: Shift toward enterprise SKUs contributed 3%       |
|                                                          |
+---------------------------------------------------------+
```

**Alternative layouts:** Formula/Waterfall (parts sum to a quantified whole, financial bridges), Matrix/Grid (two-dimensional categorization, market segmentation), Pie/Proportion (share-of-whole visualizations, max 5 segments), Issue Tree (multi-level nested decomposition).

---

## Detailed Element Guide

### Title

The title must state what is being decomposed and the key finding or insight.

**Rules:**
- Complete sentence, not a label
- Names the whole, the number of parts, and the main takeaway
- Must pass the "titles-only test"

**Formula:** `[Whole] [verb] [number] [parts descriptor]: [key insight or listing]`

**Good:** "Revenue decline driven by three factors: pricing, volume, and mix" / "Four customer segments require distinct go-to-market strategies"
**Bad:** "Revenue Breakdown" / "Customer Segments"

### Categories / Components

**Rules:**
1. **2-5 buckets ideal.** Fewer than 2 is not a decomposition. More than 5 loses clarity.
2. **Name each clearly.** Use nouns or noun phrases, parallel structure.
3. **Quantify each.** Every bucket gets at minimum a one-line description; attach a number where possible.
4. **Pass the ME test.** No item could reasonably belong to two categories.
5. **Pass the CE test.** No important item is missing from the decomposition.

**Naming:** Parallel structure ("Pricing / Volume / Mix" not "Pricing / How many units / The shift in product mix"). Same level of abstraction. Concrete over vague.

### Quantification

**Hierarchy (use the most specific available):**
1. Absolute value + percentage: "$54M (45%)" -- best
2. Percentage of whole: "45% of revenue" -- good
3. Directional with magnitude: "+5% YoY" -- acceptable
4. Rank order: "Largest contributor" -- minimum
5. No quantification: Unacceptable for analytical decks

---

## MECE Testing Guide

### The ME Test (Mutually Exclusive)

**Question:** "If I take an item from bucket A, could it also fit in bucket B?" If yes, your buckets overlap.

**Procedure:** Pick a concrete item from one bucket. Attempt to place it in every other bucket. If it fits in more than one, the decomposition fails ME.

### The CE Test (Collectively Exhaustive)

**Question:** "Can anyone in the audience think of something important that does not fit any bucket?" If yes, you are missing a bucket.

**Procedure:** Name the universe being decomposed. For each item in that universe, verify it maps to exactly one bucket. Ask: "What would a skeptical executive challenge as missing?"

### Common MECE Frameworks as Starting Points

| Framework | Categories | Best For |
|:---|:---|:---|
| **Revenue formula** | Price x Volume | Revenue decomposition |
| **P&L lines** | Revenue - COGS - SG&A - R&D = Profit | Financial decomposition |
| **Value chain** | Inbound > Operations > Outbound > Marketing > Service | Operational analysis |
| **Customer lifecycle** | Acquire > Activate > Retain > Expand > Refer | Customer metrics |
| **Geography** | Americas / EMEA / APAC | Regional analysis |
| **Internal / External** | Within our control / Outside our control | Factor categorization |
| **People / Process / Technology** | Human factors / Workflows / Tools | Operational root cause |
| **Fixed / Variable** | Does not change with volume / Changes with volume | Cost structure |

---

## Title Writing Guide

### DO Examples

1. "Revenue decline driven by three factors: pricing, volume, and mix"
2. "Four customer segments require distinct go-to-market strategies"
3. "Cost structure is 60% fixed, limiting short-term reduction options"
4. "Three root causes explain 90% of production downtime"

### DON'T Examples

1. "Revenue Breakdown" -- does not state the insight
2. "Key Factors" -- vague, does not name the factors or the finding
3. "Cost Structure" -- a label, not a conclusion
4. "Customer Segments" -- describes the slide type, not what the segments reveal

### Title Formula Patterns

| Pattern | Template | Example |
|:---|:---|:---|
| **Quantified decomposition** | "[Whole] [verb] by [N] [components]: [list]" | "Margin erosion caused by three cost categories: COGS, SG&A, and R&D" |
| **Dominant component** | "[Largest component] [verb] [whole] at [%]" | "APAC dominates revenue mix at 45% of total" |

---

## Compatibility Matrix

| Meta-Flow | Section | Compatibility | Rationale |
|:---|:---|:---|:---|
| **Pyramid Principle** | Supporting Pillars | PRIMARY | MECE structures the 2-5 pillars supporting the main recommendation |
| **SCQA** | Complication / Answer/Support | PRIMARY | Decompose the complication into MECE components; break the answer into MECE categories |
| **5 Whys** | Root Cause / Countermeasures | PRIMARY | Categorize root causes into MECE groups; organize countermeasures into MECE categories |
| **What-So What-Now What** | Now What | PRIMARY | Structure recommendations into MECE buckets |

**Also ALTERNATIVE in:** Pyramid Evidence, WSWNW What, Challenger Rational Drowning/Solution, PAS Agitate/Solution, AIDA Interest, Three-Act Act 2, Monroe Need, STAR Action.

---

## Before/After Examples

### Example 1: Revenue Decomposition

**BEFORE:**
```
Title: "Revenue Drivers"
- Sales growth in key accounts
- New product launches
- Enterprise expansion
- International markets showing strong demand
- Pricing optimization
- Customer success driving retention
```
**Problem:** Title is a label. Six items with no structure. "Key accounts" and "Enterprise expansion" overlap. Not quantified. Not clear if the list is complete.

**AFTER:**
```
Title: "Revenue growth of 12% driven by three levers,
       with volume contributing the most"

Revenue Growth: +$14.4M (+12% YoY)

+----------+  +----------+  +----------+
|  PRICE   |  |  VOLUME  |  |   MIX    |
|  +$4.8M  |  |  +$6.0M  |  |  +$3.6M  |
|  (+4%)   |  |  (+5%)   |  |  (+3%)   |
+----------+  +----------+  +----------+

Price: Premium tier repricing added $4.8M
Volume: Enterprise new logos drove $6.0M in new ARR
Mix: Shift from SMB to mid-market improved avg deal size

Total: 4% + 5% + 3% = 12% growth
```

### Example 2: Strategic Options

**BEFORE:**
```
Title: "Options for AI Capability"
Option 1: Build an internal AI team
Option 2: Acquire an AI startup
Option 3: Partner with a technology vendor
Option 4: Hire a consulting firm to build it
Option 5: Invest in an AI company and co-develop
```
**Problem:** Options 1 and 4 overlap (both are "build"). Options 2 and 5 overlap (both involve equity). Five options blur the clean strategic distinction.

**AFTER:**
```
Title: "Three paths to AI capability -- acquisition offers
       the best speed-to-market at acceptable risk"

    BUILD              BUY                PARTNER
+----------+      +----------+      +----------+
| Internal |      | Acquire  |      | JV /     |
| 18+ mos  |      | 4-6 mos  |      | license  |
| $15-20M  |      | $30-50M  |      | 6-9 mos  |
| Full ctrl|      | Owned IP |      | $5-8M/yr |
| High risk|      | Med risk |      | Low risk |
+----------+      +----------+      +----------+

Build-Buy-Partner is exhaustive: every path is organic
development, acquisition, or external alliance

>>> RECOMMENDED: Buy -- fastest path with acceptable risk
```

---

## Variations by Audience

| Audience | Bucket Count | Quantification | Title Focus |
|---|---|---|---|
| **Executive** | 2-3 max; high-level only | Required; dollar values and impact metrics | Business implication, not just decomposition |
| **Analytical** | 3-5 with sub-levels shown | Detailed; absolutes, percentages, growth rates | Can reference methodology; still requires insight |
| **Sales** | 3-4 customer-relevant segments | Customer outcomes and ROI | Emphasize customer's world, not your analysis |
| **Operations** | 3-5 aligned to process/value chain | Operational metrics (cycle time, defect rate) | Operational impact and actionability |

---

## Common Mistakes

1. **Overlapping categories.** "Marketing" and "Digital Marketing" as peers double-count. Fix: make them MECE peers or use a higher level.
2. **Missing a category (not CE).** The audience spots the gap immediately. Fix: ask "What would a skeptical executive challenge as missing?"
3. **Too many buckets (>5).** Beyond 5, the slide becomes a list, not a structured decomposition. Fix: collapse into 3-5 higher-level groups.
4. **Buckets at different levels of abstraction.** "Revenue, COGS, The Q3 supply chain issue, Overhead" mixes categories with events. Fix: every bucket must be at the same level.
5. **No quantification.** Without numbers, the audience cannot assess relative importance. Fix: attach a number to every bucket.
6. **Topic title instead of insight title.** "Cost Breakdown" forces readers to scan every element. Fix: state the finding.
7. **The "Other" bucket over 10%.** Signals incomplete analysis. Fix: break into named categories or note that no single item exceeds a threshold.

---

## Quality Checklist

**MECE Logic:**
- [ ] Categories are mutually exclusive -- no item belongs to two buckets
- [ ] Categories are collectively exhaustive -- nothing important is missing
- [ ] "Other" bucket (if present) is less than 10% of the whole
- [ ] All buckets are at the same level of abstraction
- [ ] Bucket count is between 2 and 5

**Quantification:**
- [ ] Every bucket has a number (absolute, percentage, or directional)
- [ ] Parts sum to the whole (or the delta is explained)
- [ ] Relative magnitude is visible (largest bucket is obvious)

**Title:**
- [ ] Title states the insight, not just the topic
- [ ] Title names the whole being decomposed
- [ ] Title identifies the key finding (dominant bucket, surprising result, or implication)

**Visual:**
- [ ] Visual type matches the content (tree for hierarchy, formula for additive, matrix for 2D)
- [ ] Labels are concise and parallel in structure

---

## Pro Tips

1. **Start with a known MECE framework and adapt.** Revenue = Price x Volume, Cost = Fixed + Variable, Geography = Americas + EMEA + APAC. Known frameworks are pre-validated as MECE.
2. **The "Other" bucket is a warning sign.** If "Other" exceeds 10% of the whole, your categories are not clean. Either consolidate or split "Other" into named categories.
3. **If you cannot quantify each bucket, reconsider the decomposition.** A decomposition with labels but no numbers is a taxonomy, not an analysis.
4. **Test ME by moving items between buckets.** Pick a specific item from Bucket A and try to put it in Bucket B. If it fits both, your boundaries are wrong.
5. **Test CE by playing the skeptic.** Ask: "What would a hostile questioner say is missing?" If the CFO would ask "What about FX impact?" and you have no bucket for it, your decomposition is not exhaustive.
6. **Match the visual to the math.** Additive parts: waterfall or stacked bar. Hierarchical: tree. Two-dimensional: matrix.
7. **Keep bucket names parallel.** If one bucket is a noun, all should be nouns. Parallel naming signals parallel thinking.
