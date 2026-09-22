# Scenario Builder

A skill for [Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview) and [Cowork](https://claude.ai) that builds four plausible, contrasting futures using the 2×2 critical-uncertainties method. It then turns them into early-warning indicators and robust strategic moves, so the scenarios change what you do instead of sitting in a drawer.

## What it does

Give it a decision you're facing and a horizon year. It will:

1. **Sharpen the focal question** — scenarios need a decision to serve, not just a topic
2. **Inventory 15–25 driving forces** across social, technological, economic, environmental, political and legal areas, each with a linked source (it researches them, or harvests them from a trend report or PESTLE you already have)
3. **Score impact and uncertainty**, separating *predetermined elements* (safe to plan on in every world) from *critical uncertainties*
4. **Offer 2–3 candidate axis pairs**, checking each for independence, and pause for you to choose
5. **Build four worlds**, each with a memorable name, a causal story of how we got there, winners and losers, a short vignette, and implications
6. **Critique and rewrite** against a checklist: no heaven/hell/muddle sets, no probabilities, internal consistency, every world uncomfortable for someone
7. **Write early-warning indicators** — specific, observable, sourced, and discriminating between worlds — plus search topics for a weekly signal scan and resolvable questions you could forecast
8. **Draw out robust moves**: no-regret moves, hedges, options to keep open, and big bets with their triggers

It outputs a Markdown report (easy to convert to Word) and a self-contained interactive HTML 2×2 matrix.

See [`examples/community-tool-libraries-scenarios.md`](scenario-builder/examples/community-tool-libraries-scenarios.md) for a complete worked example, built from the real example report in the [trend-report skill](https://github.com/greencat667/trend-report-skill-claude), and [`examples/community-tool-libraries-scenarios.html`](scenario-builder/examples/community-tool-libraries-scenarios.html) for its visual matrix. GitHub shows HTML files as code, so download it and open it in a browser.

## Installation

**Ask Claude to set it up for you.** If you're using Claude Code or Claude Cowork, you can just say something like *"install the scenario-builder skill from github.com/greencat667/scenario-builder-skill-claude"* and Claude will clone the repo and put it in the right place. You don't need to do this by hand.

Or do it yourself: copy the `scenario-builder/` folder into your project's `.claude/skills/` directory:

```bash
git clone https://github.com/greencat667/scenario-builder-skill-claude.git
cp -r scenario-builder-skill-claude/scenario-builder/ your-project/.claude/skills/scenario-builder/
```

Claude will pick it up automatically the next time you start a session.

## Example prompt

Once installed, just ask Claude something like:

> "Build scenarios for the future of high streets in mid-sized UK towns to 2035. We're a local development trust deciding whether to buy and run an empty shop unit as a community hub."

Or, if you already have research:

> "Use this trend report to build a 2×2 scenario set to 2036 — our decision is whether to make this our main programme."

## A note on what this is

Scenarios are not predictions, and the skill deliberately never labels a world as "most likely". Their value is in loosening the grip of the one future everyone quietly assumes, and in testing plans against several. The drivers are researched and cited, but the worlds are structured imagination. Treat them as a thinking tool for a team, ideally discussed in a workshop, not as a forecast.

## Pairs well with

- [trend-report](https://github.com/greencat667/trend-report-skill-claude) or a PESTLE scan — as input
- [strategic-wargame](https://github.com/greencat667/strategic-wargame-skill-claude) — play out the most threatening world
- [experiment-card](https://github.com/greencat667/experiment-card-skill-claude) — test the assumption behind a no-regret move
- [foresight](https://github.com/greencat667/foresight-skill-claude) — put probabilities on the forecastable questions and track them
- [trend-signal-monitor](https://github.com/greencat667/trend-signal-monitor-skill-claude) — scan the indicator topics weekly

## Repository structure

```
scenario-builder-skill-claude/
├── scenario-builder/
│   ├── SKILL.md                         # Copy this folder to .claude/skills/
│   ├── references/
│   │   ├── output-template.md           # Report structure
│   │   └── critique-checklist.md        # Step 6 checks
│   ├── assets/
│   │   └── scenario-matrix.html         # Interactive 2×2 template
│   └── examples/
│       ├── community-tool-libraries-scenarios.md
│       └── community-tool-libraries-scenarios.html
├── README.md
├── CONTRIBUTING.md
└── LICENSE
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Note that this repo isn't actively maintained, so responses to issues and PRs will be slow or may never come.

## License

MIT — see [LICENSE](LICENSE).
