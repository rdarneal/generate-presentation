# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **Claude AI Skill specification project** for generating professional presentations. There is no application code, build system, or test suite — the deliverables are structured Markdown documents that define how Claude should create presentations.

The skill uses a **two-layer compositional system**:
- **Layer 1 (Meta-Level Flows):** 10 frameworks defining overall deck architecture (choose ONE per presentation). Categories: Strategy & Consulting, Sales & Persuasion, Storytelling, Problem-Solving.
- **Layer 2 (Slide-Level Patterns):** 10 reusable patterns for structuring individual slides (mix and match within a deck).

## Repository Structure

- `SKILL.md` — Master skill definition. Primary deliverable containing the two-layer architecture, trigger conditions, core workflow, auto-selection logic, compatibility matrix, and quality standards.
- `references/meta_*.md` — Meta-flow framework templates (10 total, all complete).
- `references/slide_*.md` — Slide-level pattern templates (10 total, all complete).

## Key Conventions

- All documents are Markdown. No code files exist.
- The compatibility matrix in `SKILL.md` (which meta-flows pair with which slide patterns) must stay consistent when editing templates.
- Frameworks use specific terminology: MECE (Mutually Exclusive, Collectively Exhaustive), SCQA (Situation-Complication-Question-Answer), AIDA (Attention-Interest-Desire-Action), PAS (Problem-Agitate-Solution), etc.
- Action titles on slides should state the "so what" conclusion, not describe the content.

## Editing Guidelines

Each **meta-flow template** follows the format established in `references/meta_pyramid_principle.md` and includes: framework overview, core philosophy, complete section sequence with slide counts, when to use/avoid, compatible slide patterns by section, quality checks, and usage examples with pattern mapping.

Each **slide-pattern template** includes: pattern concept/structure, visual layout diagram, compatibility matrix with meta-flows, before/after examples, common mistakes, and audience variations.
