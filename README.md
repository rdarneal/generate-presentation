# generate-presentation

A Claude AI skill for generating professional slide decks using proven consulting, sales, storytelling, and problem-solving frameworks.

## What This Is

This is a **skill specification** for [Claude Code](https://docs.anthropic.com/en/docs/claude-code) (and compatible AI agents) that teaches Claude how to create structured presentations. There is no application code — the deliverables are Markdown documents that define presentation frameworks, patterns, and generation logic.

When installed as a Claude Code skill, typing `/generate-presentation` walks you through building a professionally structured deck using frameworks like the Pyramid Principle, SCQA, AIDA, Challenger Sale, and more.

## Two-Layer Architecture

The skill uses a compositional system that separates *deck architecture* from *slide design*:

### Layer 1: Meta-Level Flows (choose one per deck)

Overall presentation structure and narrative arc.

| Category | Frameworks |
|----------|-----------|
| Strategy & Consulting | Pyramid Principle, SCQA |
| Sales & Persuasion | Challenger Sale, AIDA, PAS |
| Storytelling | Three-Act Structure, Monroe's Motivated Sequence |
| Problem-Solving | STAR, 5 Whys, What/So What/Now What |

### Layer 2: Slide-Level Patterns (mix and match)

Reusable structures for individual slides within a deck.

| Pattern | Best For |
|---------|---------|
| Pyramid | Hierarchical arguments, MECE breakdowns |
| SCQA Micro | Setting up problem-solution slides |
| MECE | Exhaustive category breakdowns |
| BAB (Before-After-Bridge) | Transformation narratives |
| FAB (Feature-Advantage-Benefit) | Product/capability slides |
| PSB (Problem-Solution-Benefit) | Solution justification |
| STAR Micro | Evidence and case study slides |
| WSWNW (What/So What/Now What) | Data interpretation slides |
| Monroe's Visualization | Future-state contrast slides |
| 5 Whys Cascade | Root cause analysis slides |

## Repository Structure

```
SKILL.md                    # Master skill definition (primary deliverable)
references/
  meta_*.md                 # Meta-flow framework templates (10)
  slide_*.md                # Slide-level pattern templates (10)
CLAUDE.md                   # Instructions for Claude Code when working in this repo
```

## Usage

### As a Claude Code Skill

1. Add this repository's `SKILL.md` to your Claude Code skill configuration
2. Use `/generate-presentation` to invoke the skill
3. Claude will guide you through topic, audience, tone, and framework selection
4. The skill outputs structured slide content (or renders via Gamma if connected)

### As a Reference

The framework templates in `references/` are useful on their own as guides for structuring presentations manually.

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See [LICENSE.md](LICENSE.md) for details.
