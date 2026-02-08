# Pattern B: What-So What-Now What Slide Pattern

> **Note:** The `---` dividers in this file are documentation section boundaries. When generating presentation output, use `---` only as slide boundary markers per SKILL.md format rules.

## Pattern Overview

**Designation:** Pattern B (Layer 2 - Slide-Level Pattern)
**Name:** What-So What-Now What (WSWNW)
**Concept:** A single slide presents data, interprets its meaning, and recommends a specific action -- ensuring no data point appears without insight and no insight appears without a response.
**Origin:** Business communication standard; widely adopted across consulting, analytics, and data science teams.
**Best For:** Evidence slides, data findings, metric reviews, research results, KPI spotlights, any slide where a number or chart needs to drive a conclusion and an action.

**When to Use:**
- Any slide presenting quantitative or qualitative data that requires interpretation
- Evidence slides within Pyramid Principle, SCQA, or Challenger meta-flows
- Every slide in a What-So What-Now What meta-flow deck
- Slides summarizing research findings, survey results, or operational metrics
- KPI dashboards that need to go beyond reporting into advising

**When NOT to Use:**
- Pure narrative or storytelling slides (use BAB or SCQA Micro instead)
- Product feature slides (use FAB instead)
- Structural slides -- section dividers, agendas, title slides
- Visualization or future-state slides (use Monroe's Visualization instead)
- When the audience already agrees on the interpretation and just needs the recommendation (use Pyramid Principle instead)

---

## Core Philosophy

**No naked data. Every data point must be interpreted, and every interpretation must drive action.**

```
DATA  -->  INSIGHT  -->  ACTION
(What)     (So What)     (Now What)
```

1. **Data without insight is noise.** A chart showing 40% churn tells nothing about whether that is good, bad, or catastrophic until you interpret it against a benchmark, a target, or a prior period.
2. **Insight without action is academic.** Knowing that churn represents $3M in revenue at risk is useful only if paired with a specific recommendation to recover it.
3. **The chain enforces accountability.** When every data point must connect to an action, presenters naturally prune irrelevant data and sharpen vague recommendations. The three-part structure becomes a discipline, not just a format.

**The center of gravity belongs in SO WHAT and NOW WHAT, not in WHAT.** If your WHAT section dominates, you are reporting. If SO WHAT and NOW WHAT dominate, you are advising. The goal is always to advise.

**The key distinction:** A WHAT section tells the audience what happened. A SO WHAT section tells them what it means. A NOW WHAT section tells them what to do about it. All three must be present on every data slide.

---

## Visual Layout Diagram

```
+---------------------------------------------------------+
| TITLE: Q3 churn spike signals onboarding gap requiring   |
|        immediate CSM intervention                        |
+---------------------------------------------------------+
|                                                          |
| WHAT                                                     |
| [Chart: Q3 churn rate at 40%, up from 22% in Q2]       |
| Source: CRM data, Jul-Sep 2026                          |
|                                                          |
|- - - - - - - - - - - - - - - - - - - - - - - - - - - - -|
|                                                          |
| SO WHAT                                                  |
| "This represents $3M in annual revenue at risk and      |
|  indicates that customers acquired after the April       |
|  onboarding change are failing to reach activation       |
|  milestones."                                            |
|                                                          |
|- - - - - - - - - - - - - - - - - - - - - - - - - - - - -|
|                                                          |
| NOW WHAT                                                 |
| "Implement 30-day structured check-in program with      |
|  dedicated CSM touchpoints for all accounts onboarded    |
|  since April. Owner: CS Lead. Target: live by Nov 1."   |
|                                                          |
+---------------------------------------------------------+
```

**Alternative layouts:** Chart-Driven (chart left, SO WHAT/NOW WHAT right), Dashboard (2-4 metrics with mini-SO WHATs), Comparison (side-by-side data sets sharing unified SO WHAT/NOW WHAT).

---

## Detailed Element Guide

### WHAT Section (The Data)

- **One data story per slide.** Two unrelated findings = two slides.
- **Charts preferred over raw numbers.** Reserve tables for precise comparisons where the audience needs exact figures.
- **Always include units and time periods.** "$4.2M in Q3 2026, against a $4.5M target."
- **Highlight the key data point** with color, annotation, or callout. Do not make the audience hunt.
- **Include the source.** "Source: CRM data, Jul-Sep 2026."
- **Show context:** prior period, target, benchmark, or industry average -- at least one reference point.

**Good:** "Q3 churn rate: 40% (up from 22% in Q2)" -- quantified, time-bounded, contextualized.
**Bad:** "Churn has been an issue" -- no number, no timeframe, no context.

**Context Types (include at least one):**
- Prior period: "up from 22% in Q2"
- Target: "against a 15% plan"
- Benchmark: "vs 12% industry average"
- Threshold: "above the 25% board-alert level"

### SO WHAT Section (The Interpretation)

- **Must be a specific insight, not a restatement.** "Churn increased" is not interpretation. "The April onboarding redesign reduced activation by 30%, causing $3M revenue risk" is.
- **Quantify impact where possible.** Dollars, customers, percentage points at risk.
- **Connect to business context** the audience cares about -- revenue, margin, competitive position, regulatory exposure.
- **Distinguish correlation from causation** when relevant. If the link is causal, state the mechanism. If correlational, flag it.

**SO WHAT Strength Hierarchy:** Restatement (unacceptable) < Vague interpretation (weak) < Directional insight (adequate) < Quantified insight (strong) < Causal insight with impact (excellent).

**Good:** "The decline began when Q2 pricing increase took effect. Win rates dropped from 34% to 21%. This is a pricing issue, not a demand issue."
**Bad:** "Revenue declined significantly in the quarter."

### NOW WHAT Section (The Recommendation)

- **Must be specific and actionable.** "Improve onboarding" is not actionable. "Implement 30-day structured check-in program" is.
- **Include owner and timeline.** "Owner: CS Lead. Target: live by Nov 1."
- **Connect directly to the SO WHAT.** If the insight is about onboarding, the recommendation must address onboarding.
- **Use imperative language.** "Implement," "Shift," "Deploy," "Launch."
- **Quantify expected impact.** "Projected to recover $280K/quarter."
- **Pass the decidability test.** Could someone approve or reject this recommendation? If not, it is too vague.

**Good:** "Revert mid-market pricing to pre-Q2 levels. Expected recovery: $200K/quarter. Owner: VP Revenue."
**Bad:** "We should look into this further."

**NOW WHAT Completeness Test:** A strong NOW WHAT includes: (1) what to do, (2) who owns it, (3) by when, (4) expected impact. Missing any of these weakens the recommendation.

### Title

- States the overall conclusion -- typically the SO WHAT insight, the NOW WHAT direction, or both.
- Complete sentence, not a topic label. Maximum 15-20 words.
- Should make the rest of the slide optional for a time-pressed executive.

---

## The Three-Section Balance

The relative weight of WHAT, SO WHAT, and NOW WHAT signals what kind of presenter you are:

| Balance | Signal | When Appropriate |
|---|---|---|
| WHAT-heavy (60%+ of slide) | "I am a reporter" | Almost never -- data dumps belong in appendices |
| SO WHAT-heavy (50%+ of slide) | "I am an analyst" | Technical or research audiences who value interpretation |
| NOW WHAT-heavy (50%+ of slide) | "I am an advisor" | Executive audiences who need recommendations |
| Balanced (roughly equal thirds) | "I am building a case" | General audiences; early-stage recommendations |

**Default recommendation:** For most business presentations, aim for 20% WHAT, 30% SO WHAT, 50% NOW WHAT. The audience can read the data -- they need your judgment and recommendation.

---

## Title Writing Guide

### Title Formulas

**Insight-Focused:** `[Metric change] [caused by / driven by] [root cause], [representing / creating] [impact]`
Example: "Q3 churn spike is concentrated in post-April onboarding cohorts, representing $3M revenue at risk"

**Action-Focused:** `[Action verb] [specific change] to [achieve outcome] [by timeline]`
Example: "Reallocate 40% of paid search budget to organic content to reduce blended CAC by $12"

**Combined:** `[Insight] -- [recommended action]`
Example: "Rising CAC confirms channel saturation -- shift budget to organic by November"

### DO Examples

1. "Q3 churn spike is concentrated in post-April onboarding cohorts, representing $3M revenue at risk"
2. "Reallocate 40% of paid search budget to organic content to reduce blended CAC by $12"
3. "Rising CAC confirms channel saturation -- shift budget to organic by November"
4. "Mid-market revenue decline traces to Q2 pricing change -- revert pricing to recover $800K annual run rate"

### DON'T Examples

1. "Q3 Churn Data" -- describes what the slide contains, not what it concludes
2. "Quarterly Metrics" -- a topic label, not an insight
3. "Revenue Summary" -- what about revenue? up or down? why? what to do?
4. "NPS Results" -- tells me the subject, not the finding or the action needed

---

## Compatibility Matrix

| Meta-Flow | Section | Role | Rationale |
|-----------|---------|------|-----------|
| **What-So What-Now What** | What section | PRIMARY | The meta-flow's signature pattern |
| **Pyramid Principle** | Evidence slides | PRIMARY | Ensures evidence slides include interpretation and action |
| **SCQA** | Complication section | PRIMARY | Complication slides show what changed; WSWNW ensures interpretation |
| **Challenger Sale** | Impact Quantification | PRIMARY | Each hidden cost is interpreted and linked to urgency |
| **Monroe's Motivated Sequence** | Need section | PRIMARY | Need slides present evidence with interpretation |
| **STAR** | Result section | PRIMARY | Results are interpreted and connected to next steps |

**Also ALTERNATIVE in:** WSWNW So What, SCQA Support, PAS Agitate, 5 Whys Problem Statement, Three-Act Act 2, AIDA Interest.

**Universal:** Any slide in any meta-flow that presents data should follow WSWNW discipline.

---

## Before/After Examples

### Example 1: Financial Data

**BEFORE:**
```
Title: Q3 Revenue by Product Line
[Table of numbers with no interpretation or recommendation]
```

**AFTER:**
```
Title: Mid-market revenue decline of $200K traces to Q2 pricing
       change -- revert pricing to recover $800K annual run rate

WHAT
- Mid-market dropped 15.4% ($1.3M to $1.1M) while enterprise grew 7.7%
- Mid-market accounts for 100% of the shortfall
Source: Finance, Jul-Sep 2026

SO WHAT
"The decline began when Q2 pricing increase took effect. Win rates
dropped from 34% to 21%. Enterprise was unaffected (grandfathered).
This is a pricing issue, not a demand issue."

NOW WHAT
"Revert mid-market pricing to pre-Q2 levels immediately. Expected
recovery: $200K/quarter ($800K annualized). Owner: VP Revenue."
```

### Example 2: Customer Metrics

**BEFORE:**
```
Title: Customer Satisfaction Survey Results
- Overall NPS: 61 (down from 72)
- Product satisfaction: 78/100
- Onboarding satisfaction: 48/100
```

**AFTER:**
```
Title: NPS decline from 72 to 61 is driven by onboarding experience,
       not product quality -- onboarding redesign needed within 60 days

WHAT
- NPS dropped 11 points (72 to 61), largest single-quarter decline
- Onboarding satisfaction at 48/100 (lowest, down from 69)
- Product satisfaction held at 78/100 (stable)
Source: Q3 Customer Survey, n=1,247

SO WHAT
"The decline is isolated to post-purchase experience. Customers
acquired since April rate setup 30% lower. Product scores are stable.
At current trajectory, NPS drops below board threshold by Q1 2027."

NOW WHAT
"Redesign onboarding flow with guided setup and milestone tracking.
Owner: Head of CS. Timeline: 60 days. Expected: recover 8-10 NPS
points within two quarters."
```

---

## Variations by Audience

| Audience | WHAT Weight | SO WHAT Weight | NOW WHAT Weight | Key Adjustments |
|---|---|---|---|---|
| **Executive** | 20% | 30% | 50% | Compress data, expand action with decision ask and ROI |
| **Analytical / Technical** | 40% | 40% | 20% | Add methodology, confidence intervals, limitations |
| **Sales / External** | 20% | 50% | 30% | Frame as prospect's opportunity/risk, use their language |
| **Operations** | 30% | 20% | 50% | Detailed NOW WHAT with owner, process change, success metric |

---

## Common Mistakes

1. **Naked data (WHAT without SO WHAT).** Presenting a chart with no interpretation. Fix: ask "What does this mean for the business?" If you cannot answer, the data may not belong in the deck.
2. **SO WHAT that restates the data.** "Churn has increased significantly" is not interpretation -- it is a restatement. Fix: answer WHY it changed, WHAT it costs, or WHAT happens if we do nothing.
3. **NOW WHAT too vague.** "We should look into this" cannot be approved or rejected. Fix: add what specifically, who owns it, by when, and expected impact. Apply the decidability test.
4. **Too much data in WHAT.** Multiple unrelated metrics on one slide dilutes every insight. Fix: one data story per slide. Split multi-metric slides.
5. **Missing causal link between SO WHAT and NOW WHAT.** The recommendation does not address the cause identified in the interpretation. Fix: insert "therefore" between them -- if it does not connect, revise the NOW WHAT to match the SO WHAT.

---

## Quality Checklist

- [ ] All three elements (WHAT, SO WHAT, NOW WHAT) are present
- [ ] Chart or data visualization present with labeled axes, source, and highlighted key data point
- [ ] SO WHAT is genuine insight, not restatement (answers Why? What does it cost? What happens if we do nothing?)
- [ ] Business impact is quantified in SO WHAT (dollars, customers, percentage points)
- [ ] NOW WHAT is specific and actionable (passes decidability test)
- [ ] Owner and timeline identified in NOW WHAT
- [ ] NOW WHAT logically follows from SO WHAT (passes "therefore" test)
- [ ] Title states the key insight, action, or both
- [ ] Title is a complete sentence, not a topic label
- [ ] Visual hierarchy is clear (audience eye flows through three sections in order)

---

## Pro Tips

1. **Write the SO WHAT first, then find the data that supports it.** This prevents data foraging and ensures every chart earns its place on the slide.
2. **If your NOW WHAT does not follow from your SO WHAT, your logic chain is broken.** Insert "therefore" between them -- if it sounds forced, revise. The "therefore" test is the most reliable diagnostic for WSWNW slides.
3. **The SO WHAT is where you add value.** Anyone can build a chart. Anyone can pull a metric from a dashboard. Your analytical judgment about what the data means is why you are presenting -- not the data itself.
4. **Quantify the cost of inaction in the SO WHAT.** "$3M in annual revenue at risk" is more compelling than "this is a problem we should address." Quantified risk creates urgency that vague concern cannot.
5. **Match depth to audience.** Executives: 20% WHAT, 30% SO WHAT, 50% NOW WHAT. Analysts: 40% WHAT, 40% SO WHAT, 20% NOW WHAT. Sales: 20% WHAT, 50% SO WHAT, 30% NOW WHAT.
