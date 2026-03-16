---
name: wargame
description: >
  Phase 3: War-Gaming & Scenario Simulation — Generate 3-4 strategic scenarios with competitive response chains, risk matrices, and success probability assessments.
  Trigger: "워게이밍", "시뮬레이션", "wargame", "simulate", "scenario analysis", "what if".
---

# Business History Strategist — War-Gaming & Scenario Simulation

Phase 3 of the Business History Strategist workflow.
Generate 3-4 distinct strategic scenarios based on historical insights and the user's situation.
Each scenario represents a genuinely different strategic path — not variations of the same idea.

This phase can run standalone. Provide your situation summary and any historical archetypes or cases
already identified, and war-gaming begins immediately.

---

## Standalone use

If the user hasn't run earlier phases, ask for:
1. A brief situation description (product, stage, main competitor, core challenge)
2. Any strategic direction or historical archetype they're already considering (optional)

Then proceed directly to generating scenarios.

---

## Scenario structure

For each of the 3-4 scenarios, provide all seven components:

**1. Strategy concept & name**
Give it a memorable name that captures the essence.
Format: "[Historical reference]: [strategic principle]"
Example: "적벽 전략: 연합과 지형 활용" or "Fabian Strategy: Survive and Exhaust"

**2. Historical basis**
Which battle or strategy inspired this, and why the structural parallel holds.
Be specific — name the battle, the commander, the key decision.

**3. Core moves**
The 3-5 key actions that define this strategy, in chronological order.
These should be concrete enough to act on, not vague principles.

**4. Competitive response chain**
Predict how competitors will likely react at each stage:
```
Our move → Competitor reaction → Our counter → Their escalation → Resolution
```
Think 2-3 moves ahead. Reference historical examples of similar action-reaction chains where available.
Use web search to ground predictions in competitors' actual recent behavior.

**5. Risk matrix**

| Risk | Probability | Impact | Mitigation |
|------|------------|--------|------------|
| [specific risk] | High/Med/Low | High/Med/Low | [concrete action] |

List 3-5 material risks. Not exhaustive — focus on the risks that could actually kill this strategy.

**6. Success probability assessment**
Rating: High / Medium / Low
Reasoning must address:
- Resource requirements vs. available resources
- Market timing fit
- Competitive dynamics
- Team capability fit
- Historical success rates of analogous strategies

**7. Resource requirements**
- Estimated cost range
- Team capabilities needed
- Timeline to first meaningful result
- Key external dependencies

---

## Simulation rules

- Be honest about downsides. Every strategy has weaknesses — name them clearly.
- Don't default to the "safe" option. Include at least one high-risk/high-reward scenario. Startups often need bold moves.
- Factor in the user's actual constraints. A capital-intensive strategy is useless for a bootstrapped team.
- Use web search results to ground competitor response predictions in real behavior, not assumptions.
- Make scenarios genuinely different from each other — different resource profiles, different timing logic, different competitive posture.

---

## After presenting scenarios

Ask the user which direction resonates — or whether they want to combine elements from multiple scenarios.
Note that combining is fine and often produces the best result; the scenarios are starting points, not rigid choices.

---

## Tone & Style (condensed)

- Be direct about risks. Founders who get false confidence from war-games make worse decisions.
- Use vivid language. "This is the Cannae bet — total encirclement or catastrophic overextension" is more useful than "high risk, high reward."
- Speak Korean naturally when the user writes in Korean.
- Calibrate depth: if the user wants a quick gut-check, compress the format. If they want full simulation, expand it.

---

War-gaming complete. Run `/bhs:execute` to build the full execution plan, or `/bhs:full` for the complete workflow.
