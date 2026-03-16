# Business History Strategist

### *When history's greatest generals meet your startup's toughest decisions*

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/beomwookang/business-history-strategist)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Plugin-orange.svg)](https://claude.ai/code)
[![Archetypes](https://img.shields.io/badge/archetypes-15-purple.svg)](references/pattern-library.md)
[![Cases](https://img.shields.io/badge/case%20studies-40%2B-red.svg)](references/modern-cases.md)

> *"Supreme excellence consists in breaking the enemy's resistance without fighting."*
> — Sun Tzu, 孫子兵法

A Claude Code plugin that applies **battle-tested strategic principles** — from Hannibal's double envelopment to Airbnb's regulatory pivot — to your real business challenges. Not generic MBA frameworks. Deep structural pattern matching, competitive war-gaming, and actionable execution roadmaps.

---

## Why This Exists

Most strategy advice is either too abstract ("build a moat") or too tactical ("run more A/B tests"). What's missing is the middle layer: **structural pattern recognition** — understanding *why* certain competitive dynamics play out the way they do, using the clearest examples history has to offer.

Hannibal didn't just beat Rome at Cannae. He solved a resource-inferiority problem with tactical innovation. Yi Sun-sin didn't just win at Myeongnyang. He turned a 13-vs-133 disadvantage into a terrain advantage. These aren't war stories. They're **generalizable strategic frameworks** — and they map directly onto startup competition, market entry, price wars, and platform battles.

This plugin exists to make that translation automatic.

---

## Quick Start

### Via Plugin Marketplace (Recommended)

```bash
/plugin marketplace add beomwookang/business-history-strategist
```

```bash
/plugin install business-history-strategist@beomwookang-business-history-strategist
```

The skill is then available as `/business-history-strategist:business-history-strategist`.

### Manual Installation

```bash
git clone https://github.com/beomwookang/business-history-strategist.git
```

**Project-level** (current project only):
```bash
cp -r business-history-strategist/ .claude/skills/business-history-strategist/
```

**User-level** (available in all projects):
```bash
cp -r business-history-strategist/ ~/.claude/skills/business-history-strategist/
```

---

## How It Works

The plugin runs a structured four-phase workflow — from raw situation to a full execution plan.

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│   Phase 1          Phase 2          Phase 3          Phase 4   │
│                                                                 │
│   DIAGNOSE    →    MATCH      →    WAR-GAME    →    EXECUTE    │
│                                                                 │
│   Gather your    Find analogous    Simulate 3-4      Deliver   │
│   battlefield    battles &         scenarios with    report,   │
│   picture        patterns          risk mapping      roadmap   │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

**Phase 1 — Situation Diagnosis**
Choose a Quick Briefing (conversational Q&A) or Full Briefing (structured template). Live web searches pull in the latest competitor intel, funding news, and market trends.

**Phase 2 — Historical Pattern Matching**
Your situation is classified into one or more of 15 strategic archetypes and matched with 2-3 structurally analogous historical cases. Deep structural parallels — not surface-level metaphors.

**Phase 3 — War-Gaming**
3-4 distinct scenarios generated, each with: competitive response chains (2-3 moves ahead), risk matrices with probability/impact ratings, success probability assessments, and full resource requirements.

**Phase 4 — Strategy & Outputs**
Three deliverables: a Markdown strategic report, an interactive strategy visualization, and a milestone-driven execution roadmap with decision gates.

---

## What's Inside

| | |
|---|---|
| **15 Strategic Archetypes** | From resource-inferior challenger to M&A strategy — every major competitive situation mapped |
| **40+ Modern Case Studies** | Airbnb, Notion, Tesla, Slack, SpaceX, Netflix, Uber, and more — with structural analysis |
| **100+ Sub-Tactics** | Detailed, named tactical moves under each archetype |
| **7 Industry Patterns** | SaaS, Marketplace, Hardware, D2C, Fintech, AI/ML, Healthcare — each with industry-specific dynamics |
| **60+ Named Principles** | From "Feint East, Strike West" to "Crossing the Chasm" — precisely named and reusable |
| **30+ Historical Battles** | Eastern and Western classics with full structural breakdowns |

---

## Strategic Archetypes

All 15 archetypes in the pattern library, each with historical cases, modern business mappings, and detailed sub-tactics:

| # | Archetype | Core Situation | Signature Cases |
|---|-----------|---------------|-----------------|
| 1 | **Resource-Inferior Challenger** | Small startup vs. well-funded incumbent | 명량해전, Cannae, Red Cliffs |
| 2 | **Market Creation & Blue Ocean** | Competing in an undefined market | Warring States alliances, Nintendo Wii |
| 3 | **Speed & First-Mover Advantage** | Racing to capture territory before others arrive | Alexander the Great, Blitzkrieg |
| 4 | **Defense & Moat Building** | Protecting a hard-won position | Byzantine Empire, Fabian Strategy |
| 5 | **Alliance & Partnership Strategy** | Building coalitions to counter a dominant force | Red Cliffs, Jang Bogo, Three Kingdoms |
| 6 | **Disruption from Below** | Attacking from the bottom of the market up | 36 Stratagems, Christensen's framework |
| 7 | **Pivot & Strategic Retreat** | Transforming under pressure | Golden Cicada, Nine Variations |
| 8 | **Psychological & Perception Warfare** | Winning the narrative, not just the product battle | Sun Tzu's Use of Spies, D-Day deception |
| 9 | **Platform & Ecosystem Dominance** | Building the platform others depend on | Warring States diplomacy, modern network effects |
| 10 | **Survival Under Siege** | Extending the runway when under existential threat | Economy of Force, Fabius Maximus |
| 11 | **M&A and Acquisition Strategy** | Growing through deals — acqui-hires, roll-ups, strategic buys | Warring States consolidation |
| 12 | **Price War & Economic Warfare** | Fighting on cost when competitors try to undercut | Scorched earth, exhaustion strategy |
| 13 | **Talent War & Team Building** | Winning the people battle in a competitive hiring market | Gwanggaeto's elite corps, Three Visits |
| 14 | **Regulatory & Political Strategy** | Navigating or shaping the legal/regulatory environment | Machiavelli's The Prince, diplomatic alliances |
| 15 | **International Expansion & Multi-Market Strategy** | Entering new geographies with asymmetric risk | Alexander's campaigns, T.E. Lawrence |

---

## Historical Sources

### Eastern Classics
- **孫子兵法 (Sun Tzu's Art of War)** — 13 chapters, the most referenced strategic text in history
- **36 Stratagems (三十六計)** — 36 classical Chinese tactical deceptions, from "Kill with a borrowed knife" to "Empty City Strategy"
- **五輪書 (The Book of Five Rings)** — Miyamoto Musashi's combat philosophy on timing and posture
- **三國志 (Three Kingdoms)** — Battle of Red Cliffs, Three Visits to the Thatched Cottage, Battle of Guandu
- **戰國策 (Strategies of the Warring States)** — Vertical and horizontal alliances, coalition warfare
- **Korean Military History** — Yi Sun-sin's 명량해전 (Battle of Myeongnyang, 1597), Gwanggaeto the Great's expansion campaigns, Jang Bogo's maritime network strategy

### Western Classics
- **Clausewitz's On War** — Fog of war, friction, center of gravity, culminating point
- **Machiavelli's The Prince** — Fortune and virtue, the fox and the lion, political realism
- **Hannibal Barca** — Battle of Cannae (216 BC), double envelopment, tactical innovation under resource constraint
- **Alexander the Great** — Speed as a strategic weapon, decisive action, psychological dominance
- **Napoleon Bonaparte** — Interior lines strategy, corps system, the strategic reserve
- **T.E. Lawrence** — Guerrilla warfare, asymmetric tactics, the value of mobility over mass
- **Modern Operations** — D-Day's Operation Bodyguard (strategic deception), asymmetric warfare doctrine

### Modern Case Studies
40+ structured analyses of modern business battles, including:

| Company | Strategic Situation Modeled |
|---------|----------------------------|
| Airbnb | Regulatory warfare and narrative strategy |
| Notion | Late-mover disruption in a mature SaaS market |
| Tesla | Vertical integration as competitive moat |
| Slack | Bottom-up enterprise infiltration |
| SpaceX | Cost-structure disruption in a government-dependent industry |
| Netflix | Sequential market pivot (DVD → streaming → content) |
| Uber | Regulatory arbitrage and speed-of-deployment strategy |
| Stripe | Developer-first ecosystem building |
| Figma | Collaborative wedge into an entrenched market |
| Duolingo | Gamification as retention moat |

### Industry-Specific Patterns
Seven industry playbooks with dynamics, failure modes, and historical analogues unique to each:

`SaaS` · `Marketplace` · `Hardware` · `D2C` · `Fintech` · `AI/ML` · `Healthcare`

---

## Usage Examples

Drop any of these into Claude Code after installing — the skill activates automatically:

```
"I'm a small startup competing against DoorDash in food delivery.
 Help me build a real strategy using historical parallels."
```

```
"We're entering B2B SaaS where Salesforce dominates.
 Simulate 3 market entry scenarios and tell me which to run."
```

```
"A well-funded competitor just copied our core feature.
 What's our counter-move? War-game this for me."
```

```
"We have 6 months of runway. Should we pivot or double down?
 Use historical survival strategies to frame the decision."
```

```
"Big Tech just entered our AI startup's market.
 Give me a defense strategy grounded in how smaller forces
 have beaten larger ones throughout history."
```

```
"We're expanding into Southeast Asia from the US.
 Map out an international expansion strategy with risk scenarios."
```

---

## Project Structure

```
business-history-strategist/
├── .claude-plugin/
│   ├── plugin.json                  <- Plugin manifest
│   └── marketplace.json             <- Marketplace listing
├── SKILL.md                         <- Main workflow engine (Phases 1-4)
├── references/
│   ├── pattern-library.md           <- 15 archetypes with historical mappings
│   ├── modern-cases.md              <- 40+ modern business case studies
│   ├── industry-patterns.md         <- 7 industry-specific strategic playbooks
│   ├── eastern-classics.md          <- Eastern strategic traditions in full
│   ├── western-classics.md          <- Western strategic traditions in full
│   └── output-templates.md          <- Report, visualization & roadmap templates
├── README.md
└── LICENSE
```

---

## Contributing

The reference library grows with contributions. High-value areas:

- **New historical cases** — battles or campaigns with clear business structural parallels
- **Modern case studies** — recent competitive situations with documented outcomes
- **Industry patterns** — playbooks for industries not yet covered
- **Archetype refinements** — sharper sub-tactics or better historical matches
- **Output templates** — new visualization formats or report structures

Open a PR with a clear description of what you're adding and why it improves pattern coverage.

---

## License

MIT — use it, fork it, build on it.
