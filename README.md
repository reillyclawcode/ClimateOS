# ClimateOS — Climate Futures Dashboard

**Explore climate scenarios, biodiversity, emissions, sea level rise, agriculture, and resource projections across multiple possible futures.**

ClimateOS is the environmental intelligence layer of the [AI Civilization](https://reillyclawcode.github.io/clawcodeblog/research/ai-civilization/) framework. It models four divergent climate futures — from aggressive global action (1.5°C pathway) to worst-case feedback loops (>4°C) — and visualizes how each scenario impacts temperature, sea level, CO₂, biodiversity, crop yields, water stress, forest cover, and critical mineral supply chains.

## Dashboard Tabs

| Tab | What it shows |
|-----|---------------|
| **Overview** | Current planetary metrics, temperature trajectories, tipping points |
| **Scenarios** | Four futures side-by-side — temperature, sea level, CO₂, biodiversity, renewables, crops, water, forests |
| **Biodiversity** | Species threatened, ecosystem status, restoration project progress |
| **Energy & Emissions** | Grid mix, sectoral emissions, historical trends, renewable pathways |
| **Resources** | Water stress, agriculture, critical minerals for the energy transition |
| **Timeline** | Climate action milestones from 2026 to 2050 |

## Scenarios Modeled

- **Aggressive Action** 🌟 — Net-zero by 2040, massive reforestation, +1.2°C by 2050
- **Moderate Transition** ⚡ — Paris targets met, fossil phase-out by 2060, +1.8°C by 2050
- **Business as Usual** 🏭 — Current policies continue, +3.0°C by 2050
- **Worst Case** 🔥 — Feedback loops triggered, +4.6°C by 2050

## Quick Start

```bash
npm install
npm run dev
# → http://localhost:3000
```

## Tech Stack

- **Next.js 14** with App Router
- **React 18** + TypeScript
- **Tailwind CSS 3** (glassmorphism dark theme)
- **Recharts** for all data visualizations

## Ecosystem

ClimateOS is part of the AI Civilization research ecosystem:

- [Simulation Dashboard](https://simulation-tau-dun.vercel.app/) — Branching futures, structural metrics, 50-year horizon
- [TransitionOS](https://transition-os-beta.vercel.app/) — Workforce transitions, reskilling, income bridges
- [CivilizationOS](https://civilization-os-3nlf.vercel.app/) — Resident journeys, civic dividends, benefits, KPIs
- [GovernanceOS](https://civilization-os-ashy.vercel.app/) — Charter frameworks, assemblies, audit tracking
- [Research Paper](https://reillyclawcode.github.io/clawcodeblog/research/ai-civilization/) — Full theory and implementation roadmap
- [Clawcode Blog](https://reillyclawcode.github.io/clawcodeblog/) — All posts and commentary

## License

MIT
