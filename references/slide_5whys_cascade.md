# Slide Pattern H: 5 Whys Cascade Slide Pattern

> **Note:** The `---` dividers in this file are documentation section boundaries. When generating presentation output, use `---` only as slide boundary markers per SKILL.md format rules.

## Pattern Overview

**Designation:** Pattern H (Layer 2 -- Slide-Level Pattern)
**Concept:** A single slide that visually traces a chain of causation from an observable symptom through successive "Why?" questions down to a systemic root cause. The cascade makes every causal link visible, auditable, and traceable.
**Origin:** Toyota Production System / Taiichi Ohno / Lean Manufacturing methodology.
**Best For:** Root cause analysis, incident postmortems, operational reviews, quality audits, process improvement proposals, engineering retrospectives.

**When to Use:**
- You need to show *how* you arrived at a root cause, not just state it
- The audience may be skeptical and needs to see the logic chain
- The problem has a predominantly linear cause-effect structure
- You are presenting within the Why Cascade section of a 5 Whys meta-flow deck

**When NOT to Use:**
- The problem has many independent causes at the first level (use Fishbone/Ishikawa instead)
- You already know the root cause and the audience does not need the derivation (use Pyramid Principle)
- The slide is meant to state a recommendation or solution (use PSB or Pyramid)
- The "why" chain would require more than 6-7 layers (problem is too broad)

---

## Core Philosophy

**Symptoms mislead; root causes solve.** The cascade makes the logic chain visible, forcing rigorous causal thinking at every step.

The 5 Whys Cascade exists because visual chains beat narrative explanations for root cause communication:

1. **Every link is auditable.** Stakeholders can point to a specific link and challenge it. A paragraph buries connections in syntax; a cascade exposes them.
2. **Logical leaps become impossible to hide.** The cascade format requires you to show each step, forcing you to verify each step.
3. **The audience follows the reasoning in real-time.** Each "Why?" creates a micro-question; the next layer answers it. This question-answer rhythm builds trust incrementally.
4. **The root cause earns its emphasis.** By the bottom of the cascade, the root cause feels inevitable, not asserted.
5. **Blame is structurally difficult.** Each layer asks "why did this happen?" not "who did this?" -- naturally driving toward systemic thinking.

**Fundamental rule:** Each "Why?" must represent a genuine causal link -- not a correlation, not a guess, not an assumption. If you cannot provide evidence for a link, it is a hypothesis, not a finding.

---

## Visual Layout Diagrams

### Layout 1: Vertical Cascade (Primary)

```
+----------------------------------------------------------+
|  Response time degradation traces to missing capacity      |
|  planning process in product launch workflow               |
+----------------------------------------------------------+
|                                                            |
|  PROBLEM: Support response time increased from 2hr         |
|  to 8hr in Q3, breaching SLA for 340 enterprise accounts  |
|                                                            |
|      | Why?                                                |
|                                                            |
|  1. Tier 1 queue depth grew 3x while staffing              |
|     remained flat                                          |
|                                                            |
|      | Why?                                                |
|                                                            |
|  2. Ticket volume increased 45% due to new product         |
|     launch adoption                                        |
|                                                            |
|      | Why?                                                |
|                                                            |
|  3. Product launch planning did not include a support      |
|     capacity forecast                                      |
|                                                            |
|      | Why?                                                |
|                                                            |
|  +------------------------------------------------------+  |
|  |  ROOT CAUSE: Launch planning checklist has no         |  |
|  |  mandatory support readiness gate -- staffing was     |  |
|  |  never assessed for volume impact                     |  |
|  +------------------------------------------------------+  |
|                                                            |
|  Source: Queue analytics; headcount records; launch docs    |
+----------------------------------------------------------+
```

**Alternative layouts:** Horizontal Flowchart (left-to-right for wide screens), Fishbone/Branching (chain splits into parallel root causes), Numbered Layers with Indentation (text-heavy for async reading), Summary Table (compact Layer/Finding/Evidence table for executives).

---

## Detailed Element Guide

### Problem Statement

Must describe an observable symptom -- something measured, detected, or reported -- not a suspected cause.

- **Specific, quantified symptom:** what happened, how much, over what period
- **Observable fact,** not an interpretation or theory
- **Must not embed a cause** ("Response time increased because of staffing cuts" is wrong)
- **Include impact:** financial cost, customer effect, SLA breach, volume affected
- **Define scope:** time range, affected products/regions/teams

**Good:** "Customer support response time increased from 2hr to 8hr in Q3, breaching SLA for 340 enterprise accounts"
**Bad:** "Things are slow" / "The team made mistakes" / "Response time increased because we cut headcount"

### Why Layers (3-5 typically)

Each layer answers "Why did the previous statement happen?" with an evidence-backed finding.

- **Direct causal answer** to the previous layer, not a tangential observation
- **Verifiable and testable** -- could someone confirm or disprove this?
- **Evidence, not assumptions:** data, logs, interviews, process documentation
- **Quantification** wherever possible: "grew 3x," "increased 45%," "set in 2019"
- **Reverse test:** "Because [this layer], therefore [the previous layer]" must be logically true
- **3-5 layers typical;** fewer than 3 = stopped at symptom; more than 7 = scope too broad

### Root Cause

The final layer -- the systemic, process-level, or design-level issue where the cascade terminates.

- **Systemic or process issue** -- never an individual's error or personality trait
- **Actionable:** the team can design and implement a countermeasure
- **Visually emphasized:** bold, boxed, labeled "ROOT CAUSE:"
- **Classification** when useful: process gap, system limitation, policy gap, design flaw

**Root Cause Tests:** (1) Is this a process/system issue, not an individual? (2) Can we change this? (3) Would fixing this have prevented the original problem? (4) Does going deeper reach speculation or unfixable abstractions?

### Title

States the root cause finding, not a topic label. Complete sentence, specific enough that a reader understands the diagnosis from the title alone.

---

## When to Stop Guide

**Stop when:**
1. **You have reached a systemic cause** -- a gap in a process, system, policy, or design
2. **The cause is actionable** -- you can write a concrete action item
3. **The chain explains the symptom when traced forward** (reverse test)
4. **Going further reaches unfixable abstractions** ("humans make mistakes," "budgets are finite")

| Depth | Finding | Verdict |
|---|---|---|
| Why 1 | Queue depth grew 3x | Too early -- symptom |
| Why 2 | Ticket volume surged with product launch | Too early -- observation |
| Why 3 | Launch planning excluded support forecast | Too early -- explains what, not why process failed |
| Why 4 | Launch checklist has no support readiness gate | **Just right** -- process gap, actionable |
| Why 5 | Nobody thought to add it when checklist was created | Too deep -- reaches "human oversight" |

---

## Title Writing Guide

### DO Examples

1. "Response time degradation traces to missing capacity planning process in product launch workflow"
2. "Fulfillment delays caused by inventory sync frequency never updated after SKU count tripled"
3. "Invoice errors stem from manual pricing upload with no automated sync to source of truth"
4. "Production outage rooted in deployment process lacking mandatory performance validation"

### DON'T Examples

1. "Root Cause Analysis" -- what is the root cause?
2. "5 Whys Investigation" -- tells the method, not the finding
3. "Incident Review" -- what did the review find?
4. "Why Did This Happen?" -- asks a question instead of answering it

---

## Compatibility Matrix

| Meta-Flow | Section | Role | Rationale |
|---|---|---|---|
| **5 Whys** | Why Cascade | PRIMARY | Purpose-built pattern for the cascade section |
| **SCQA** | Complication | ALTERNATIVE | Use when complication involves diagnosing why a problem exists |
| **SCQA** | Support | ALTERNATIVE | Root cause analysis as part of evidence supporting the answer |
| **WSWNW** | What | ALTERNATIVE | Use when the "What" involves problem analysis showing causation |
| **Pyramid** | Supporting Pillars | ALTERNATIVE | Use when a pillar is a root cause argument |
| **Challenger** | Reframe | ALTERNATIVE | Show why the customer's assumed cause is wrong and the real root cause is systemic |

**Also ALTERNATIVE in:** PAS Problem, Monroe Need, Three-Act Act 2, STAR Action.

**Summary:** Pattern H is purpose-built for root cause analysis sections. It serves as an alternative in any meta-flow where a causal chain supports the section's argument. Not used for recommendation, solution, or emotionally driven slides.

---

## Before/After Examples

### Example 1: Production Incident

**BEFORE:**
```
Title: "Root Cause Analysis"
Root cause: Lack of monitoring.
- The payment system went down
- It was caused by a database issue
- We need better monitoring
```

**AFTER:**
```
Title: "4-hour payment outage traces to deployment process
lacking mandatory performance validation for DB changes"

PROBLEM: Payment processing down 4 hours, affecting
12,400 transactions ($890K in delayed revenue)

    | Why?
1. DB connection pool exhausted -- all 200 connections
   held by a single runaway query

    | Why?
2. Query deployed without a timeout parameter, holding
   connections indefinitely under load

    | Why?
3. Query deployed without load testing -- passed unit
   tests but never tested at scale

    | Why?
+-----------------------------------------------------+
|  ROOT CAUSE: Deployment checklist has no mandatory    |
|  performance validation gate for database-touching    |
|  changes -- queries can reach production without      |
|  load testing                                         |
+-----------------------------------------------------+

Source: Incident #4472 postmortem; deployment SOP v3.1
```

### Example 2: Customer Churn

**BEFORE:**
```
Title: "Churn Analysis"
- Enterprise churn increased in H1
- Customers are unhappy with onboarding
- We need to improve the customer experience
```

**AFTER:**
```
Title: "Enterprise churn traces to absent product-to-CS
handoff process -- onboarding never updated after Q1
product redesign"

PROBLEM: Enterprise churn doubled from 5% to 10% in H1,
representing $3.8M in lost ARR

    | Why?
1. 72% of churning customers (34 of 47) cited poor
   onboarding as primary factor

    | Why?
2. Onboarding materials referenced features and UI
   that changed in the Q1 product redesign

    | Why?
3. Product and CS teams have no formal handoff process
   for UX changes -- CS was not notified

    | Why?
+-----------------------------------------------------+
|  ROOT CAUSE: No formalized process for product       |
|  changes to trigger CS content and training updates   |
|  -- cross-team communication relies on ad-hoc Slack   |
+-----------------------------------------------------+

Source: Churn survey (n=47); CS/Product process review
```

---

## Variations by Audience

| Audience | Format | Depth | Evidence | Title Style |
|---|---|---|---|---|
| **Executive** | Summary cascade, one slide | 3-4 layers max | Reference evidence types briefly; point to appendix | Root cause + business impact |
| **Operations / Engineering** | Full cascade or one-slide-per-why | Full 5+ layers | Specific data: logs, config settings, timestamps | Can be technical and detailed |
| **Cross-Functional** | Summary + 1-2 deep-dive slides | 3-5 layers, plain language | Avoid jargon; focus on systemic descriptions | Plain language, systemic finding |
| **External / Client** | Summary with emphasis on fix | 3-4 layers, concise | Omit sensitive internal details | Diplomatic and forward-looking |

---

## Common Mistakes

1. **Jumping to root cause without intermediate layers.** No logic chain means the audience takes the diagnosis on faith. Fix: show 3-5 intermediate steps.
2. **Correlations, not causes.** "Marketing campaign launched" is not a cause of response time increase. Fix: state the direct causal mechanism.
3. **Blaming individuals instead of systems.** "Sales reps used old data" stops too early. Fix: ask why the system allowed the error to happen.
4. **Stopping too early (symptom-level root cause).** "Ticket volume increased" is not a root cause. Fix: keep asking why until you reach a process gap.
5. **Going too deep (unfixable abstractions).** "Humans have limited foresight" produces no countermeasure. Fix: stop at the last actionable layer.
6. **Causal leaps between layers.** Two adjacent layers have a gap in logic. Fix: fill every intermediate step.
7. **No evidence supporting causal links.** A cascade of opinions, not findings. Fix: cite data, logs, or documentation at each layer.

---

## Quality Checklist

- [ ] Problem is stated as an observable, quantified symptom (no embedded cause)
- [ ] Impact is quantified (financial, operational, or customer-facing)
- [ ] Each layer directly answers "Why did the previous layer happen?"
- [ ] Each layer is supported by cited evidence
- [ ] No causal leaps -- every step is logically connected
- [ ] No layer blames an individual -- all causes are systemic
- [ ] Chain contains 3-5 layers (not too shallow, not too deep)
- [ ] Reverse test passes: reading root cause forward produces the original problem
- [ ] Root cause is a process, system, policy, or design issue
- [ ] Root cause is actionable by the presenting team
- [ ] Root cause is visually emphasized (bold, box, label)
- [ ] Title states the root cause finding, not a topic label
- [ ] Evidence sources are cited in the footer

---

## Pro Tips

1. **Test every link by reading in reverse.** "Because [root cause], therefore [Layer N-1], therefore ... therefore [original problem]." If any "therefore" does not follow, the link is wrong.
2. **Quantify every layer if possible.** "The sync ran once per day instead of real-time, creating up to 23 hours of data lag" beats "the process was slow."
3. **Highlight the root cause visually.** Use a box, bold text, or "ROOT CAUSE:" label. The reader's eye should land there before scanning intermediate layers.
4. **State the root cause in the title.** If the title says "Root Cause Analysis," the audience must scan the entire slide. If it says "Response time degradation traces to missing capacity planning," they know the answer immediately.
5. **One slide for executives, one-per-why for engineering.** Same investigation, two zoom levels.
6. **When the chain branches, follow the dominant path.** List secondary branches as contributing factors on the same slide or a follow-up. If both branches are equally important, use two cascade slides.
7. **Always pair with a countermeasure slide.** The cascade diagnoses; the countermeasure cures. A cascade without a following countermeasure leaves the audience with a problem and no solution.
