# What-So What-Now What Presentation Template

> **Note:** The `---` dividers in this file are documentation section boundaries. When generating presentation output, use `---` only as slide boundary markers per SKILL.md format rules.

## Framework Overview
**Origin:** Business communication standard, widely used in analytics and data teams
**Best For:** Data presentations, research readouts, analytics reviews, quarterly business reviews
**Audience:** Analysts, managers, VPs, cross-functional stakeholders, data-oriented executives
**Duration:** 5-15 slides (10-30 minutes typical)

## Core Philosophy
Present the facts. Interpret what they mean. Recommend what to do about it.

Every data point earns its place only if it leads to an insight, and every insight earns its place only if it drives an action. The center of gravity belongs in "So What" and "Now What," not in "What."

---

## Slide Structure Template

### 1. TITLE SLIDE
**Elements:**
- Analysis/review topic name
- Time period covered (quarter, campaign window, etc.)
- Date, presenter, team name

**Title Pattern:**
*"Q3 2026 Customer Acquisition Analysis: Paid Channels Underperforming Relative to Organic"*

---

### 2. CONTEXT SLIDE (1 slide)
**Purpose:** Frame the analysis — why this was done, what data was examined, what the audience needs to know before diving in

**Content Requirements:**
- Scope of analysis (time period, data sources, segments covered)
- Business question being addressed or trigger for the review
- Any key definitions, methodology notes, or caveats

**Title Pattern:**
*"This review covers Q3 paid acquisition across all channels against our $50 CAC target"*

---

### 3-6. WHAT SECTION (2-4 slides, ~30% of deck)
**Purpose:** Present the data, facts, and findings — the raw material for interpretation

**Content Requirements:**
- Key metrics and trends
- Data visualizations (charts, tables, graphs)
- Comparisons (period-over-period, segment-to-segment, actual-vs-target)
- Factual observations — what happened, not why
- Lead with the most important finding first
- One key finding per slide — if a finding does not lead to a distinct insight in So What, move it to appendix

**Title Pattern:** Factual observation stating what the data shows
*"Paid search CAC rose 34% quarter-over-quarter while volume declined 12%"*
*"Customer NPS dropped from 72 to 61 across all segments in Q3"*

---

### 7-11. SO WHAT SECTION (3-5 slides, ~40% of deck)
**Purpose:** Interpret the findings — explain what the data means, why it matters, and what the implications are for the business

**Content Requirements:**
- Cause analysis: why did this happen?
- Business impact: what does this mean in dollars, customers, risk, or opportunity?
- Pattern identification: what trends or themes connect the findings?
- Comparison to expectations: is this better or worse than planned, and by how much?
- Distinguish between correlation and causation explicitly

**Title Pattern:** Interpretive statement explaining the meaning or implication
*"Rising CAC signals channel saturation — we are hitting diminishing returns on paid search"*
*"The NPS decline is concentrated in post-onboarding experience, not product quality"*

---

### 12-15. NOW WHAT SECTION (2-4 slides, ~30% of deck)
**Purpose:** Translate insights into concrete, actionable recommendations and next steps

**Content Requirements:**
- Specific recommended actions (not vague suggestions)
- Prioritization: which actions first, which can wait
- Ownership: who is responsible for each action
- Timeline: when should each action happen
- Expected impact: what will improve and by how much
- Recommendations should be MECE — no overlap, no gaps
- Include both quick wins (next 30 days) and longer-term structural changes

**Title Pattern:** Directive statement recommending a specific action
*"Reallocate 40% of paid search budget to organic content — projected to reduce blended CAC by $12"*
*"Launch targeted onboarding intervention for mid-market segment within 30 days"*

**Typical Structure (Summary/Roadmap Slide):**
```
[Action title summarizing the action plan]

IMMEDIATE (0-30 days)
- Action 1 — [owner] — [expected impact]
- Action 2 — [owner] — [expected impact]

SHORT-TERM (30-90 days)
- Action 3 — [owner] — [expected impact]

DECISION NEEDED
[Specific approval or resource request]
```

---

## APPENDIX (Optional, not presented)
- Detailed data tables and additional cuts
- Methodology and data source documentation
- Sensitivity analysis or alternative scenarios
- Backup slides for anticipated questions

---

## Section-Specific Title Guidance

**Context titles** should state the scope and framing:
- "This analysis covers Q3 performance across all paid channels against a $50 CAC target"

**What titles** should state what the data shows (factual, observable):
- "Email open rates declined 15% while unsubscribe rates doubled"

**So What titles** should state why it matters (interpretive, causal):
- "The email decline reflects list fatigue from Q2 over-sending, not content quality"

**Now What titles** should state what to do about it (directive, actionable):
- "Reduce email frequency to 2x/week and implement engagement-based segmentation"

---

## Quality Checks

Before finalizing:

**Section Balance:**
- [ ] "What" section is no more than 30% of total slides
- [ ] "So What" section is the largest section (~40%)
- [ ] "Now What" section has concrete, actionable recommendations

**Logic Chain:**
- [ ] Every "What" finding connects to at least one "So What" insight
- [ ] Every "So What" insight connects to at least one "Now What" recommendation
- [ ] No orphan findings (data shown but never interpreted)
- [ ] No orphan recommendations (action proposed without supporting insight)

**Clarity:**
- [ ] Every slide title is a complete sentence stating a conclusion
- [ ] A reader can follow the full narrative from titles alone
- [ ] Data visualizations are immediately readable (labeled axes, clear legends, highlighted takeaway)
- [ ] All charts include source, time period, and units
- [ ] Confidence levels are stated when interpretation involves uncertainty

**Data Integrity:**
- [ ] All charts include source, time period, and units
- [ ] Comparisons use appropriate baselines (not cherry-picked)
- [ ] Percentage changes include absolute numbers for context

**Actionability:**
- [ ] Recommendations are specific (who, what, when, expected impact)
- [ ] Priorities are clear (what first, what later)
- [ ] Success metrics are defined for key recommendations
- [ ] There is a clear ask or decision point for the audience

---

## Common Patterns by Data Type

### Performance Review (Quarterly Business Review)
1. Context: Review scope and KPI targets
2. What: Performance vs. targets across key metrics
3. So What: Root causes of over/underperformance; trend implications
4. Now What: Course corrections, resource reallocation, updated targets

**Example Arc:**
- Context: "Q3 review covers revenue, retention, and efficiency against annual plan"
- What: "Revenue hit 94% of target; retention exceeded plan; CAC missed by 22%"
- So What: "CAC overrun driven by paid channel saturation — organic pipeline underinvested"
- Now What: "Shift 30% of paid budget to organic; hire content lead by end of Q4"

### Market Research
1. Context: Research objectives and methodology
2. What: Market size, segments, trends, competitive landscape
3. So What: Strategic implications — where to play, threats, whitespace opportunities
4. Now What: Market entry recommendations, positioning strategy, investment priorities

**Example Arc:**
- Context: "Assessed European fintech market for potential 2027 entry"
- What: "Market is $14B and growing 23% CAGR; three segments, two dominant incumbents"
- So What: "SMB segment is underserved — incumbents focused on enterprise; regulatory window opens in Q2 2027"
- Now What: "Enter via SMB segment with localized product; target $8M ARR in Year 1"

### Customer Analytics
1. Context: Analysis trigger and customer segments examined
2. What: Behavioral data — engagement, churn, satisfaction, usage patterns
3. So What: Customer health diagnosis — at-risk segments, growth segments, root causes
4. Now What: Retention interventions, expansion plays, product changes

**Example Arc:**
- Context: "Analyzed churn spike in mid-market segment triggered by Q2 support ticket surge"
- What: "Mid-market churn rose from 4% to 9%; correlated with onboarding completion drop"
- So What: "New onboarding flow reduced completion by 30% — churners never reached activation milestones"
- Now What: "Roll back onboarding flow; implement guided setup for at-risk accounts within 2 weeks"

---

## Adaptation Notes

**Shorter Decks (5-8 slides):**
- Compress Context into a single framing sentence on the title slide
- Limit What to 1-2 slides with the most critical findings only
- Combine So What insights into a single thematic slide
- Keep Now What to 1 slide with prioritized actions

**Extended Decks (13-15 slides):**
- Expand What section with additional data cuts (max 4 slides)
- Break Now What into immediate actions and strategic initiatives
- Maximum 15 slides; move additional data to appendix

**For Executive Audiences (VP+):**
- Lead with a combined "So What + Now What" summary slide immediately after Context
- Compress What section — executives trust your data; they want interpretation
- End with a clear decision ask, not just "next steps"

**For Technical / Analyst Audiences:**
- Expand What section with methodology details and data quality notes
- So What section can dive deeper into causal analysis
- Audience expects and values the data — don't over-compress What

**For Recurring Reviews:**
- Standardize slide structure across periods
- Highlight what changed since last review
- Include a running "action tracker" showing status of prior recommendations

---

## Template Usage Example

**Topic:** "Q3 2026 E-commerce Conversion Rate Analysis"

**What-So What-Now What Structure:**

### Context
- **Slide 1 (Context):** "This analysis examines the Q3 conversion rate decline across web and mobile against our 3.2% annual target"
  - Scope: All channels, July-September 2026
  - Trigger: Conversion rate dropped below 3.0% for the first time in 6 quarters

### What Section
- **Slide 2:** "Overall conversion rate fell from 3.4% to 2.7% — a 21% decline concentrated in August-September"
  - Chart: Monthly conversion rate trend, 6 quarters
  - Pattern: What-So What-Now What slide pattern

- **Slide 3:** "Mobile conversion dropped 31% while desktop held steady at 3.3%"
  - Chart: Conversion by device type, side-by-side
  - Pattern: What-So What-Now What slide pattern

- **Slide 4:** "Cart abandonment rate spiked to 78% on mobile — up from 62% baseline"
  - Chart: Abandonment funnel comparison, pre vs post redesign
  - Pattern: What-So What-Now What slide pattern

### So What Section
- **Slide 5:** "The redesign broke the mobile checkout flow — payment form does not render correctly on iOS Safari"
  - Root cause: CSS rendering issue on iOS 17+
  - Impact: Estimated $340K revenue loss in Q3
  - Pattern: Pyramid Principle slide pattern

- **Slide 6:** "Desktop stability proves the core value proposition is intact — the issue is execution, not demand"
  - Interpretation: Traffic and intent metrics unchanged; conversion failure is mechanical
  - Pattern: Pyramid Principle slide pattern

- **Slide 7:** "If unresolved, Q4 mobile losses will reach $580K due to holiday traffic concentration"
  - Projection: Q4 mobile traffic is historically 2.1x Q3
  - Pattern: Pyramid Principle slide pattern

- **Slide 8:** "Secondary factor: new payment provider integration added 1.4 seconds to mobile load time"
  - Data: Each second of load time reduces conversion by ~7%
  - Pattern: Pyramid Principle slide pattern

### Now What Section
- **Slide 9:** "Fix the iOS Safari rendering issue within 5 business days — estimated to recover $280K/quarter"
  - Owner: Front-end engineering team; Timeline: Immediate
  - Pattern: Problem-Solution-Benefit slide pattern

- **Slide 10:** "Optimize payment provider integration to reduce mobile load time to pre-redesign baseline"
  - Owner: Platform engineering; Timeline: 2-3 weeks
  - Pattern: Problem-Solution-Benefit slide pattern

- **Slide 11:** "Implement mandatory cross-device QA gate before any future checkout changes ship"
  - Owner: QA lead + engineering manager; Timeline: 2 weeks
  - Pattern: Problem-Solution-Benefit slide pattern

- **Slide 12:** "Summary: three actions to recover $340K+ in quarterly revenue and prevent recurrence"
  - Decision ask: Approve emergency hotfix deployment and QA process change
  - Pattern: MECE Decomposition slide pattern

**Slide Count:** 12 slides (Context: 1, What: 3, So What: 4, Now What: 4)

---

## Compatible Slide Patterns

| Section | Primary Pattern | Alternative Pattern | Why |
|---------|----------------|--------------------|----|
| **Context** | SCQA Micro-Narrative (E) | Pyramid Principle (A) | Frames why this analysis matters now |
| **What** | What-So What-Now What (B) | Pyramid Principle (A) | Micro-interpretation on each data slide prevents naked data |
| **So What** | Pyramid Principle (A) | MECE Decomposition (D) | Insight-first titles; MECE for grouping implications |
| **Now What** | Problem-Solution-Benefit (J) | MECE Decomposition (D) | Structures each recommendation; MECE for summary/roadmap |

---

## Final Pro Tips

1. **Fight "What bloat" ruthlessly.** If your What section is longer than your So What section, move findings to the appendix. The audience can read data; they need your interpretation.

2. **Write the So What section first.** List your 3-5 key insights before building slides, then select only the data that supports those insights for the What section.

3. **Every chart needs a "so what" in the title.** Never title a chart "Q3 Revenue by Channel." Instead: "Organic channel drove 68% of Q3 revenue growth while paid channels declined."

4. **Use the "therefore" test between sections.** Read What findings, say "therefore" before So What insights, then "therefore" before Now What recommendations. If "therefore" doesn't connect them, you have a logic gap.

5. **Quantify the cost of inaction in So What.** Converting implications into dollar amounts or competitive risk makes Now What recommendations feel necessary rather than optional.

6. **Make Now What slides decidable.** Every recommendation should be specific enough for the audience to say "yes, approved" or "no, rejected." "Shift $200K from paid search to content marketing by November 1" is decidable.

7. **Close the loop on prior recommendations.** For recurring reviews, start with a status update on prior recommendations. This builds credibility and shows the WSWNW cycle is producing real outcomes.
