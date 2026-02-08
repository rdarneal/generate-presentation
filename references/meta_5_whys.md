# 5 Whys Root Cause Investigation Template

> **Note:** The `---` dividers in this file are documentation section boundaries. When generating presentation output, use `---` only as slide boundary markers per SKILL.md format rules.

## Framework Overview
**Origin:** Toyota Production System; developed by Taiichi Ohno as a core tool in lean manufacturing and continuous improvement (kaizen)
**Best For:** Root-cause analysis presentations, operational incident postmortems, process improvement proposals, quality failure reviews
**Audience:** Operations teams, engineering leads, quality assurance, senior management (operational reviews), cross-functional improvement teams
**Duration:** 5-12 slides (10-25 minutes typical)

## Core Philosophy
Dig beneath symptoms to find the systemic cause. Fix the system, not the person.

**Three Pillars:**
1. **Systems Thinking** --- Every outcome is produced by a system. Blame the system, not the person operating it.
2. **Causal Discipline** --- Each "why" must follow logically from the previous answer. No leaps, no speculation without evidence.
3. **Actionability** --- The investigation is only as good as the countermeasure it produces. When you reach a cause that is both **systemic** and **actionable**, you stop.

---

## Slide Structure Template

### 1. TITLE SLIDE
**Elements:**
- Investigation or review title
- Problem identifier (incident number, defect ID, project name)
- Date, presenter(s), team or department

**Title Pattern:**
*"Root Cause Analysis: Q3 Order Fulfillment Delays"*

---

### 2. PROBLEM STATEMENT (1 slide)
**Purpose:** Establish a precise, measurable description of the problem

**Content Requirements:**
- Clear, specific statement of what went wrong (do not embed a suspected cause)
- Quantified impact (financial, operational, customer-facing)
- When the problem was detected and its duration or frequency
- Scope: what is affected and what is not

**Title Pattern:**
*"Order fulfillment cycle time increased 40%, causing 1,200 late shipments in Q3"*

**Typical Structure:**
```
PROBLEM
[Precise description of the observed failure or deviation]

IMPACT
[Quantified consequences: cost, volume, customer effect, SLA breach]

SCOPE
[Time range, affected products/regions/teams, frequency]
```

---

### 3-7. WHY CASCADE (3-5 slides)
**Purpose:** Walk the audience through the chain of causation from observable symptom to systemic root cause

**Content Requirements per "Why" Slide:**
- The question being asked at this layer ("Why did X happen?")
- The answer, supported by evidence (data, logs, interviews, observations)
- A clear logical link to the next layer
- Evidence type noted (data analysis, process review, interview, direct observation)

**Title Pattern:** Statement of the cause discovered at each layer
*"Warehouse pick lists were generated with outdated inventory data"*
*"Inventory system sync runs only once per day instead of real-time"*

**Typical Structure per Slide:**
```
WHY [N]: [Question]
"Why did [previous answer] happen?"

FINDING
[Answer with evidence]

EVIDENCE
[Data source, measurement, or observation that supports this finding]

LINK TO NEXT
→ This leads us to ask: Why did [this finding] occur?
```

**Presentation Format Options:**
- **Option A: One Slide Per Why** --- Best for detailed reviews. Each why gets full evidence. 3-5 slides.
- **Option B: Cascading Single-Slide Summary** --- Best for executive audiences. All whys on one slide as a vertical chain. Detail in appendix.
- **Option C: Hybrid** --- Summary cascade slide + detail slides for critical layers. Best for mixed audiences.

**When to Stop:** You've reached a process/policy/system design issue that is actionable by your team. Typically 3-5 layers. If the chain becomes circular or speculative, you've gone too far.

**Branching:** If a "why" has multiple contributing causes, follow the dominant branch to root cause and note secondary branches as contributing factors for follow-up.

---

### 8. ROOT CAUSE (1 slide)
**Purpose:** Clearly state the systemic root cause and why the investigation stops here

**Content Requirements:**
- Definitive root cause statement
- Classification (process gap, system limitation, policy gap, design flaw, training gap)
- Evidence summary connecting the root cause to the original problem
- Why this is the right level to stop (actionable, systemic, within scope)

**Title Pattern:**
*"Inventory sync frequency was never updated when SKU count tripled, creating systematic data lag"*

**Typical Structure:**
```
ROOT CAUSE
[Clear, specific statement of the systemic issue]

CLASSIFICATION
[Process gap | System limitation | Policy gap | Design flaw | Training gap]

EVIDENCE CHAIN SUMMARY
Problem → Why 1 → Why 2 → ... → Root Cause

WHY WE STOP HERE
[This is actionable by our team and addresses a system/process design]
```

---

### 9-11. COUNTERMEASURES (2-3 slides)
**Purpose:** Present specific, actionable interventions that address the root cause and prevent recurrence

**Content Requirements:**
- Each countermeasure tied directly to the root cause (not to intermediate symptoms)
- Owner, timeline, and success metric for each
- Distinction between immediate containment and permanent fix
- Risk or trade-off assessment for each countermeasure

**Title Pattern:**
*"Migrating to real-time inventory sync eliminates the data lag that caused fulfillment delays"*

**Typical Structure:**
```
COUNTERMEASURES OVERVIEW

1. [Immediate containment action] — Owner — By [date]
2. [Permanent process fix] — Owner — By [date]
3. [Preventive system change] — Owner — By [date]

Each addresses: [Root cause statement]
```

---

### 12. IMPLEMENTATION (1-2 slides)
**Purpose:** Define how and when countermeasures will be executed, and how effectiveness will be verified

**Content Requirements:**
- Phased timeline with milestones
- Resource requirements (budget, headcount, tools)
- Verification plan: how you will confirm the root cause is resolved
- Escalation path if countermeasures do not produce expected results
- Review cadence

**Title Pattern:**
*"Three-phase rollout over 6 weeks with verification gate at each stage"*

**Typical Structure:**
```
IMPLEMENTATION ROADMAP

Phase 1: [Immediate / Containment] — Week 1-2
  - [Action items]

Phase 2: [Permanent Fix] — Week 3-4
  - [Action items]

Phase 3: [Verification & Monitoring] — Week 5-6
  - [Verification criteria]

REVIEW DATE: [When team reconvenes to assess effectiveness]
ESCALATION: [What happens if metrics don't improve]
```

---

## APPENDIX (Optional, not presented)
- Full investigation notes and interview transcripts
- Detailed data analysis supporting each "why" layer
- Alternative root causes considered and why they were ruled out
- Historical trend data and related incidents

---

## Quality Checks

Before finalizing:

**Causal Logic:**
- [ ] Problem statement is specific, measurable, and does not embed a presumed cause
- [ ] Each "why" follows logically from the previous answer (no leaps)
- [ ] Evidence supports each layer (not speculation or assumption)
- [ ] Root cause is systemic (process/system/policy), not individual blame
- [ ] Root cause is actionable by the team presenting

**Completeness:**
- [ ] The chain reaches a sufficient depth (at least 3 layers)
- [ ] The chain does not go too deep (stops at actionable system cause)
- [ ] No intermediate layers are skipped

**Countermeasures:**
- [ ] Every countermeasure ties directly to the root cause (not a symptom)
- [ ] Each has an owner, timeline, and success metric
- [ ] Containment vs. permanent fix distinction is clear
- [ ] Countermeasures are collectively sufficient to prevent recurrence

**Presentation:**
- [ ] Slide titles alone tell the full story (problem → cause chain → root cause → fix → plan)
- [ ] Evidence is quantified where possible
- [ ] No blame language (names individuals as responsible for failure)
- [ ] Implementation has a verification and review mechanism

---

## Common Patterns by Problem Type

### Production Incident / System Outage
1. **Problem:** Service outage lasting X hours affecting Y users
2. **Why Cascade:** Symptom → immediate technical cause → configuration/deployment gap → process gap → organizational root cause
3. **Countermeasures Pattern:** Automated checks, alerting improvements, runbook updates

**Example Chain:**
- Problem: Payment processing was down for 4 hours
- Why 1: Database connection pool was exhausted
- Why 2: A query was running without a timeout
- Why 3: The query was deployed without load testing
- Why 4: No load testing requirement exists in the deployment checklist
- Root Cause: Deployment process lacks mandatory performance validation for database-touching changes

### Customer Churn / Retention Issue
1. **Problem:** Churn rate increased by X% over Y period
2. **Why Cascade:** Churn metric → customer behavior pattern → product/service gap → internal process gap → strategic root cause
3. **Countermeasures Pattern:** Customer journey redesign, product roadmap adjustment, support process improvement

**Example Chain:**
- Problem: Enterprise churn doubled from 5% to 10% in H1
- Why 1: Churning customers cited poor onboarding experience
- Why 2: Onboarding was not updated after the Q1 product redesign
- Why 3: Product and CS teams have no formal handoff process for UX changes
- Root Cause: No formalized process for product changes to trigger customer success updates

### Process Failure / Operational Error
1. **Problem:** Error rate in process X exceeded threshold
2. **Why Cascade:** Error observation → immediate cause → process gap → design or training gap → systemic root
3. **Countermeasures Pattern:** Process automation, SOP revision, ownership clarification, quality gates

**Example Chain:**
- Problem: 15% of invoices in March contained incorrect pricing
- Why 1: Sales reps applied outdated discount schedules
- Why 2: The updated pricing sheet was not loaded into the quoting tool
- Why 3: Pricing updates require a manual upload by the RevOps team
- Root Cause: Pricing system relies on manual data entry with no automated sync to the source of truth

---

## Adaptation Notes

**Shorter Presentations (5-8 slides):**
- Compress Why Cascade to a single cascading visual (Option B)
- Combine Root Cause and Countermeasures into one slide
- Skip separate Implementation slide; add "Next Steps" to Countermeasures

**Extended Presentations (11-15 slides):**
- Use one slide per "why" with full evidence (Option A)
- Add a "Timeline of Events" slide after Problem Statement
- Include a "Lessons Learned" slide after Implementation
- Maximum 15 slides; move data deep-dives to appendix

**For Executive Audiences:**
- Lead with impact quantification
- Use single-slide cascade (Option B) or hybrid (Option C)
- Frame countermeasures in terms of risk reduction and business impact
- Consider a Pyramid Principle executive summary slide before the problem statement

**For Operations Teams:**
- Full technical detail in the Why Cascade
- Include raw data, logs, metrics in evidence
- Implementation should include specific tool changes, SOP updates, and configuration details

---

## Template Usage Example

**Topic:** "Root Cause Analysis: Customer Support Response Time Degradation"

**Problem Statement:**
- Average first-response time for Tier 1 support tickets increased from 2 hours to 8 hours over Q2-Q3, breaching the 4-hour SLA for 340 enterprise accounts

**Why Cascade:**

| Layer | Question | Finding | Evidence |
|-------|----------|---------|----------|
| Why 1 | Why did response time increase? | Tier 1 queue depth grew 3x while staffing remained flat | Queue analytics dashboard; headcount records |
| Why 2 | Why did queue depth grow 3x? | Ticket volume increased 45% due to new product launch | Ticket volume trending correlated with launch dates |
| Why 3 | Why wasn't staffing scaled? | Product launch planning did not include support capacity forecast | Launch planning documents (no CS capacity section) |
| Why 4 | Why was support excluded? | Launch checklist does not include a support readiness gate | Current checklist template review |

**Root Cause:**
- Product launch process lacks a mandatory support readiness assessment

**Countermeasures:**
1. **Immediate:** Hire 4 contract Tier 1 agents (Owner: CS Director, 2 weeks, Metric: queue depth to baseline)
2. **Process Fix:** Add "Support Capacity Forecast" to launch checklist (Owner: Product Ops, 30 days, Metric: all launches include plan)
3. **Preventive:** Automated alerting when queue exceeds 150% capacity (Owner: Engineering, 45 days, Metric: alert within 1 hour)

**Implementation:** Phase 1 (W1-2): Contract staffing → Phase 2 (W3-4): Checklist update → Phase 3 (W5-6): Alerting deployed → 60-day review

**Slide Count:** 10 slides (Title: 1, Problem: 1, Why Cascade: 4, Root Cause: 1, Countermeasures: 2, Implementation: 1)

**Pattern Mapping:**
- Problem Statement → SCQA Micro-Narrative
- Why 1-4 → 5 Whys Cascade (one per slide with evidence)
- Root Cause → Pyramid Principle
- Countermeasures → MECE Decomposition + Problem-Solution-Benefit
- Implementation → Pyramid Principle

---

## Compatible Slide Patterns by Section

| Section | Primary Pattern | Alternative Pattern | Why |
|---------|----------------|--------------------|----|
| **Problem Statement** | SCQA Micro-Narrative | Problem-Solution-Benefit (problem portion) | Frames problem with context |
| **Why Cascade** | 5 Whys Cascade | What-So What-Now What (per layer) | Cascade for visual chain; WSWNW if layers need data interpretation |
| **Root Cause** | Pyramid Principle | MECE Decomposition (if multiple roots) | Root cause as title, evidence chain as support |
| **Countermeasures** | MECE Decomposition + Problem-Solution-Benefit | Pyramid Principle | MECE ensures completeness; PSB structures each intervention |
| **Implementation** | Pyramid Principle | STAR Micro-Case (if referencing past rollout) | Action title with phased timeline |

---

## Final Pro Tips

1. **Write the root cause first, then build backward.** Build your presentation by deciding the root cause slide first, then constructing the chain that leads to it. This ensures narrative coherence.

2. **Test the chain in reverse.** Read from root cause back to problem. Each step should answer "and therefore what happened?" If it doesn't flow, a logical link is broken.

3. **Quantify every layer.** "The sync ran once per day" is stronger than "the sync was infrequent." Each finding should include a number, date, or specific observation.

4. **Never name individuals as the root cause.** If your chain ends at "John made an error," ask why the system allowed that error to have consequences.

5. **Separate containment from cure.** Present both the immediate fix (fire is out) and the permanent fix (building is fireproofed), clearly labeled.

6. **Prepare for "why didn't you go deeper?"** The strongest answer: "At this level we reach a process design choice our team can change, and changing it prevents this failure."

7. **Use the appendix aggressively.** Move data tables, log excerpts, and interview notes to the appendix. The main deck should be a clean narrative.
