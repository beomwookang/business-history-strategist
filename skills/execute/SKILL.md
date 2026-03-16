---
name: execute
description: Phase 4 Strategy Formulation — Build execution plans with reports, visualizations, and roadmaps
---

# Business History Strategist — Strategy Formulation & Output Generation

Phase 4 of the Business History Strategist workflow.
Once a strategic direction is chosen (from war-gaming or directly provided), build the full execution strategy
and deliver all three output artifacts.

This phase can run standalone. Provide your chosen strategy or scenario, and execution planning begins immediately.

---

## Standalone use

If the user hasn't run earlier phases, ask for:
1. The strategic direction or approach they've chosen
2. Their key constraints (budget, team size, timeline)
3. What success looks like at 1 year and 3 years

Then proceed directly to building the execution plan.

---

## Time horizons

Structure all planning across three horizons:

- **Short-term (0-3 months)**: Immediate actions, quick wins, validation steps — what to do this week and this quarter
- **Mid-term (3-12 months)**: Core strategy execution, key milestones, scaling triggers
- **Long-term (1-3 years)**: Vision, target market position, strategic pivots to prepare for

For each horizon, include:
- **Objectives**: What you're trying to achieve in this period
- **Key actions**: The 3-5 concrete moves that matter most
- **Success metrics (KPIs)**: How you'll know if it's working
- **Decision gates**: Conditions that trigger strategy adjustment (e.g., "if we reach X, do Y; if we don't, do Z")
- **Resource allocation**: Where time, money, and attention go

---

## Output deliverables

Produce all three of these for every execution plan:

### 1. Strategic Report (Markdown)

For output format and section templates, refer to `references/output-templates.md`.

Structure:
```
# [Company/Product] Strategic Battle Plan
## Executive Summary (1 paragraph)
## Battlefield Assessment (current situation)
## Historical Intelligence (analogies and insights)
## Recommended Strategy
### Strategic Scenarios Evaluated
### Selected Approach & Rationale
## Execution Plan
### Short-term (0-3 months)
### Mid-term (3-12 months)
### Long-term (1-3 years)
## Risk Register & Contingencies
## Key Decision Gates
```

Save as a Markdown file and present to the user.

### 2. Strategy Visualization

Create a React or HTML artifact showing:
- A strategy map that visually connects historical insight → strategic principle → concrete action
- The competitive response chain as an interactive flowchart
- The risk matrix as a visual heat map

Use inline diagrams during the conversation for quick reference.
Create a comprehensive standalone artifact for the full visualization.

For visualization templates, refer to `references/output-templates.md`.

### 3. Execution Roadmap (Timeline)

Create a visual timeline artifact showing:
- All three time horizons with key milestones marked
- Decision gates clearly labeled
- Dependencies between actions
- Resource allocation over time

The roadmap should be interactive — the user should be able to see what happens in each phase at a glance.

For roadmap templates, refer to `references/output-templates.md`.

---

## Quality standards for deliverables

- Every action item must be executable with the user's actual resources — no "hire a VP of Sales" for a bootstrapped team
- Decision gates must be specific and measurable, not vague ("if traction looks good")
- Risk register must include contingency actions, not just risk labels
- The executive summary should be writable on a single slide — it's a forcing function for clarity

---

## Tone & Style (condensed)

- Lead with the plan, not the framework. Users want to know what to do Monday morning.
- Be direct about resource trade-offs. Every choice means not doing something else — name those trade-offs.
- Speak Korean naturally when the user writes in Korean.
- Keep the executive summary genuinely executive: one crisp paragraph, no jargon.

---

Strategy formulation complete. Your deliverables are ready.
