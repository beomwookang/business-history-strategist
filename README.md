# Business History Strategist

> Classical warfare wisdom meets modern business strategy simulation

A Claude Code skill that applies **battle-tested strategic principles** from Sun Tzu, Clausewitz, Machiavelli, the 36 Stratagems, Yi Sun-sin, Three Kingdoms, and more to your real business challenges — complete with **scenario simulation, risk/probability analysis, and actionable roadmaps**.

## Who Is This For?

**Startup founders and early-stage teams** who need sharp, realistic strategy — not generic MBA frameworks.

- You have limited resources and need to outmaneuver larger competitors
- You want to simulate competitive responses before committing to a strategy
- You need a structured approach to market entry, expansion, or pivot decisions
- You believe that history's most proven strategies can illuminate today's business battles

## Installation

### Via Plugin Marketplace (Recommended)

This repo serves as both a plugin and a marketplace. Add it with a single command inside Claude Code:

```bash
/plugin marketplace add beomwookang/business-history-strategist
```

Then install the plugin:

```bash
/plugin install business-history-strategist@beomwookang-business-history-strategist
```

Once installed, the skill is available as `/business-history-strategist:business-history-strategist`.

### Manual Installation

If you prefer to install without the marketplace:

```bash
git clone https://github.com/beomwookang/business-history-strategist.git
```

#### Project-level (current project only)

```bash
cp -r business-history-strategist/ .claude/skills/business-history-strategist/
```

#### User-level (available in all projects)

```bash
cp -r business-history-strategist/ ~/.claude/skills/business-history-strategist/
```

## How It Works

The skill walks you through a structured four-phase workflow:

```
Phase 1: Situation Diagnosis  -->  Gather your business context
Phase 2: Historical Matching  -->  Find analogous battles & strategies
Phase 3: War-Gaming           -->  Simulate scenarios with risk mapping
Phase 4: Strategy & Outputs   -->  Deliver reports, visuals, roadmap
```

### Phase 1: Situation Diagnosis

Choose between a **Quick Briefing** (conversational Q&A) or a **Full Briefing** (structured template). The skill also runs web searches to pull in the latest market data, competitor intel, and industry trends.

### Phase 2: Historical Pattern Matching

Your situation is classified into strategic archetypes and matched with 2-3 structurally analogous historical cases. Not surface-level comparisons — deep structural parallels where power dynamics, resource ratios, and strategic options genuinely map onto your situation.

### Phase 3: War-Gaming (Scenario Simulation)

3-4 distinct strategic scenarios are generated, each including:
- **Competitive response chains** — predicting 2-3 moves ahead
- **Risk matrices** — probability, impact, and mitigation for each risk
- **Success probability assessments** — with explicit reasoning
- **Resource requirements** — cost, team, timeline, and dependencies

### Phase 4: Strategy Formulation & Outputs

The selected scenario becomes a full execution plan with three deliverables:

1. **Strategic Report** (Markdown) — executive summary through execution plan
2. **Strategy Visualization** — interactive maps, flowcharts, and risk heat maps
3. **Execution Roadmap** — timeline with milestones, decision gates, and dependencies

## Historical Sources

### Eastern Classics
- **Sun Tzu's Art of War** — 13 chapters of strategic principles
- **36 Stratagems** — 36 classical Chinese strategic deceptions
- **The Book of Five Rings** — Miyamoto Musashi's combat philosophy
- **Three Kingdoms** — Battle of Red Cliffs, Three Visits, Battle of Guandu
- **Strategies of the Warring States** — Vertical & horizontal alliances
- **Korean Military History** — Yi Sun-sin (Battle of Myeongnyang), Gwanggaeto the Great, Jang Bogo

### Western Classics
- **Clausewitz's On War** — Fog of war, friction, center of gravity
- **Machiavelli's The Prince** — Fox and lion, fortune and virtue
- **Hannibal** — Battle of Cannae (double envelopment)
- **Alexander the Great** — Speed and decisive action
- **Napoleon** — Interior lines strategy
- **T.E. Lawrence** — Guerrilla warfare principles
- **Modern Strategy** — D-Day deception, asymmetric warfare

## Pattern Categories

| # | Pattern | Core Situation | Key Examples |
|---|---------|---------------|--------------|
| 1 | Resource-Inferior Challenger | David vs Goliath | Myeongnyang, Cannae |
| 2 | Rapid Territory Expansion | Blitzkrieg | Alexander, Gwanggaeto |
| 3 | Fortification & Defense | Defending the Castle | Fabius, Byzantine Empire |
| 4 | Strategic Alliance | Alliance Building | Red Cliffs, Warring States, Jang Bogo |
| 5 | Pivot & Transformation | Metamorphosis | Golden Cicada (36 Stratagems), Nine Variations |
| 6 | Surprise & Innovation | Disruption | Feint East Strike West, Austerlitz |
| 7 | Resource Efficiency & Survival | Survival Mode | Economy of Force, Fabian Strategy |
| 8 | Information Warfare | Intelligence | Sun Tzu's Use of Spies, Enigma |

## Usage Examples

```
"I'm a small startup competing against DoorDash in the food delivery space. Help me build a strategy."

"We're entering the B2B SaaS market where Salesforce dominates. Simulate entry strategies for us."

"A competitor just copied our MVP. How should we respond?"

"We have 6 months of runway left. Should we pivot or stay the course?"

"We're an AI startup and Big Tech just entered our market. Help me build a defense strategy using historical parallels."
```

## Project Structure

```
business-history-strategist/
├── .claude-plugin/
│   ├── plugin.json                  <- Plugin manifest
│   └── marketplace.json             <- Marketplace definition
├── skills/
│   └── business-history-strategist/
│       ├── SKILL.md                 <- Main workflow engine (Phases 1-4)
│       └── references/
│           ├── eastern-classics.md  <- Eastern strategic traditions
│           ├── western-classics.md  <- Western strategic traditions
│           ├── pattern-library.md   <- Business <-> historical pattern mapping
│           └── output-templates.md  <- Report, visualization & roadmap templates
├── SKILL.md                         <- Root skill file (same as above)
├── references/                      <- Root references (same as above)
├── README.md                        <- You are here
└── LICENSE                          <- MIT License
```

## Contributing

Contributions are welcome! Here are some ways you can help:

- Add new historical cases or strategic traditions
- Expand pattern categories with new archetypes
- Improve output templates and visualizations
- Add localization support for other languages

Please open a PR with a clear description of your changes.

## License

MIT License
