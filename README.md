# claude-skills-competitor-intel

A growing collection of Claude skills for competitive intelligence — extracting insight from financial reports, earnings calls, and market data. Built for product and operations leaders who need to move fast on competitor analysis without a finance background.

Skills follow the [Agent Skills open standard](https://agentskills.io) and work across Claude.ai, Claude Code, and the Claude API.

-----

## Skills

### `annual-report-ci`

Analyses company annual reports and financial results for competitive intelligence. Extracts KPIs, runs ratio analysis, and interprets strategic positioning.

**Triggers:** “analyse [company] annual report”, “compare [companies] financials”, “pull the numbers from [company]’s results”, “run the metrics on [company]”, “what’s [company]’s ROCE / gross margin / working capital”, or pasting financial figures and asking for derived metrics, ratio analysis, or strategic interpretation.

-----

## Installation

### Claude.ai (personal)

1. Download or clone this repository
1. Zip the skill folder you want (e.g. `annual-report-ci/`)
1. Go to **Customize > Skills** in Claude.ai and upload the ZIP

### Claude.ai (Team / Enterprise)

Organisation Owners can provision skills for all users via organisation settings.

### Claude Code

```bash
# Via OpenSkills — whole repo
npx openskills install terryawebb/claude-skills-competitor-intel

# Via OpenSkills — single skill
npx openskills install terryawebb/claude-skills-competitor-intel/annual-report-ci

# Manually
cp -r annual-report-ci/ ~/.claude/skills/
```

-----

## Repository structure

```
claude-skills-competitor-intel/
├── annual-report-ci/
│   ├── SKILL.md
│   └── skill.yaml
├── README.md
├── CONTRIBUTING.md
├── .github/
│   └── PULL_REQUEST_TEMPLATE.md
└── LICENSE
```

-----

## Roadmap

Skills planned or in progress:

- `earnings-call-analysis` — extract strategic signals from earnings call transcripts
- `market-positioning` — map competitor positioning from public sources
- `investor-relations-tracker` — monitor shifts in narrative across annual reports over time

-----

## Contributing

Contributions are welcome, particularly new CI-focused skills. See <CONTRIBUTING.md> for guidelines, quality standards, and the PR process.

-----

## Licence

Skills in this repository are licensed under [Apache 2.0](LICENSE).

-----

## About

Built by [Terry Webb](https://github.com/terryawebb) — Head of Product Operations and writer at [Transformation Etiquette](https://transformationetiquette.substack.com).
