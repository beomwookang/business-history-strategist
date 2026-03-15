# Output Templates Reference

Templates and guidelines for generating the three deliverables.
Read this in Phase 4 when producing final outputs.

---

## 1. Strategic Report (Markdown)

### Template

```markdown
# 🏴 [Company/Product Name] — Strategic Battle Plan

> **Prepared**: [Date]
> **Strategic Archetype(s)**: [e.g., Resource-Inferior Challenger + Disruption from Below]
> **Time Horizon**: [e.g., 0-3 years]

---

## Executive Summary

[1 paragraph — the core strategic recommendation in plain language.
What to do, why, and what the expected outcome is.]

---

## I. Battlefield Assessment

### Current Position
- **Product/Service**: [what it is, core value]
- **Stage**: [idea / MVP / traction / growth]
- **Resources**: [team size, funding, runway]

### Market Terrain
- **Market Size**: [TAM/SAM/SOM if available]
- **Growth Trajectory**: [growing/stable/declining, rate]
- **Key Trends**: [2-3 trends shaping the market]

### Competitive Landscape
[For each major competitor:]
- **[Competitor Name]**: [their strengths, weaknesses, recent moves, likely strategy]

### Core Challenge
[The specific decision or problem this strategy addresses]

---

## II. Historical Intelligence

### Primary Analogy: [Battle/Strategy Name]
- **Historical Context**: [brief — 2-3 sentences]
- **Structural Parallel**: [why this maps to the current situation]
- **Key Lesson**: [the actionable principle]
- **Where the Analogy Breaks**: [honest limitations]

### Secondary Analogy: [Battle/Strategy Name]
[Same structure]

### Synthesized Principles
[3-5 bullet points that combine insights from all analogies into unified strategic guidance]

---

## III. Strategic Scenarios Evaluated

### Scenario A: [Name] — ⭐ Recommended
[Summary, rationale, risk level]

### Scenario B: [Name]
[Summary, rationale, risk level]

### Scenario C: [Name]
[Summary, rationale, risk level]

### Comparative Matrix

| Dimension | Scenario A | Scenario B | Scenario C |
|-----------|-----------|-----------|-----------|
| Success Probability | | | |
| Resource Requirement | | | |
| Time to Impact | | | |
| Risk Level | | | |
| Competitive Exposure | | | |

---

## IV. Recommended Strategy: [Name]

### Strategic Thesis
[2-3 sentences — the core logic of why this wins]

### Historical Foundation
[Which battles/strategies inform this and how]

---

## V. Execution Plan

### Phase 1: Short-term (0-3 months)
**Objective**: [clear, measurable]

| Week | Action | Owner | Metric | Dependencies |
|------|--------|-------|--------|-------------|
| 1-2 | | | | |
| 3-4 | | | | |
| 5-8 | | | | |
| 9-12 | | | | |

**Decision Gate**: [condition that triggers Phase 2 or pivot]

### Phase 2: Mid-term (3-12 months)
**Objective**: [clear, measurable]

[Key milestones by month]
[Resource allocation changes]
[Scaling triggers]

**Decision Gate**: [condition that triggers Phase 3 or pivot]

### Phase 3: Long-term (1-3 years)
**Objective**: [vision-level goal]

[Strategic positioning goals]
[Market share targets]
[Organizational evolution]

---

## VI. Risk Register

| # | Risk | Probability | Impact | Mitigation | Trigger Signal |
|---|------|------------|--------|------------|---------------|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |

---

## VII. Key Decision Gates

| Gate | Condition | If YES | If NO |
|------|-----------|--------|-------|
| G1 (Month 3) | | Proceed to Phase 2 | [alternative] |
| G2 (Month 12) | | Proceed to Phase 3 | [alternative] |

---

## Appendix: Historical References

[Brief descriptions of all historical cases referenced, with source texts]
```

### Report writing guidelines

- Lead with recommendations, not history. History is supporting evidence.
- Use vivid, memorable language for strategy names and concepts.
- Every action item must have an owner (role, not name), a metric, and a timeline.
- Risk register must include "trigger signals" — observable events that indicate the risk is materializing.
- Decision gates are critical. Startups that don't define pivot conditions keep going too long.

---

## 2. Strategy Visualization (React/HTML Artifact)

### Components to include

**Strategy Map**: A visual flow connecting:
```
Historical Insight → Strategic Principle → Business Action → Expected Outcome
```
Use a directed graph or Sankey-style diagram.

**Competitive Response Chain**: An interactive flowchart showing:
```
Our Move → [Competitor A likely response] → Our Counter
         → [Competitor B likely response] → Our Counter
```
Make branches expandable/collapsible.

**Risk Heat Map**: A 2D scatter plot:
- X-axis: Probability (Low → High)
- Y-axis: Impact (Low → High)
- Each risk as a labeled dot, color-coded by category
- Quadrants labeled: Monitor / Mitigate / Plan / Critical

### Design guidelines

- Use clean, professional colors — not garish startup aesthetics
- Make it interactive where it adds value (hover for details, click to expand)
- Ensure mobile readability
- Include a legend/key for any symbols or color coding

---

## 3. Execution Roadmap (Timeline Artifact)

### Structure

A horizontal timeline divided into three phases with:

**Visual elements**:
- Phase blocks with color differentiation (e.g., blue → green → purple)
- Milestone diamonds at key dates
- Decision gate markers (prominent, cannot miss)
- Dependency arrows between connected actions
- Resource allocation bar (optional, shows team/budget allocation over time)

**Information layers** (toggleable or visible on hover):
- Layer 1: High-level milestones only (default view)
- Layer 2: Detailed actions per phase
- Layer 3: Metrics and KPIs per milestone

### Timeline writing guidelines

- Milestones must be specific and measurable, not vague ("Launch MVP to 50 beta users" not "Launch MVP")
- Include both action milestones and decision milestones
- Decision gates should visually stand out — they're the most important parts
- Show the "critical path" — the sequence of tasks where any delay delays everything
