# Oceanlife

A fully referenced feasibility study for a solar-powered, self-governing floating town for 20 to 40 families: law, politics, engineering, systems, cost and choice of host country.

**Read it online: https://ts00.github.io/oceanlife/**

## The short answer

You cannot build a floating country, but you can build a floating, self-governing village. A chartered village moored in a sheltered lagoon inside a cooperating host state (Panama ranks first, narrowly) costs about **US$166m, or US$6.7m per family**, for 25 large homes on 2 ha. A denser 40-home variant costs about **US$2.9m per family**. Overall verdict: **Amber**.

## Contents

The chapters are Markdown files in [`study/`](study/), about 70,000 words with ~600 footnoted references:

| # | Chapter |
|---|---|
| 00 | [Design basis](study/00-design-basis.md) |
| 01 | [Legal status and sovereignty](study/01-legal.md) |
| 02 | [Politics, governance and society](study/02-governance-and-society.md) |
| 03 | [Site selection and platform structure](study/03-site-and-structure.md) |
| 04 | [Life-support and utility systems](study/04-systems.md) |
| 05 | [Cost, financing and economics](study/05-cost-and-economics.md) |
| 06 | [Choosing a host country](study/06-host-countries.md) |
| 07 | [A cheaper, denser village](study/07-accessible-variant.md) |
| 08 | [Synthesis and verdict](study/08-synthesis-and-verdict.md) |

## How it was made

Researched and drafted in November 2026 with AI research agents, one per domain, working from a shared design basis and reconciled by a lead author. References were link-checked and the most surprising claims re-verified against primary sources. See the [home page](study/index.md#how-this-was-made-and-its-limits) for the method and its limits. Not professional engineering, legal, tax or investment advice.

## Building the site locally

```bash
python3 -m venv .venv && . .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

The site is published to GitHub Pages by [`.github/workflows/pages.yml`](.github/workflows/pages.yml) on every push to `main`.
