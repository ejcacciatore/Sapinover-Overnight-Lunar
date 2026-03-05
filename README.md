# Sapinover Overnight Lunar | LNY 2026 Full Cycle

**On / Off / On:** 16-session overnight ATS analysis tracking aggregate flow through baseline, anticipatory decay, holiday trough, and recovery around Lunar New Year 2026.

**Live dashboard:** [ejcacciatore.github.io/Sapinover-Overnight-Lunar](https://ejcacciatore.github.io/Sapinover-Overnight-Lunar/)

---

## What This Is

An event study examining how overnight U.S. equity trading volume on Alternative Trading Systems responds to Asian market closures during Lunar New Year. The analysis covers 16 sessions from February 2–24, 2026, decomposed into four phases.

## Headline Numbers

| Metric | Value |
|--------|-------|
| Sessions analyzed | 16 |
| Observations | 251,600 |
| Baseline average | $6.3B per session |
| Pre-holiday average | $3.2B (49% decay, 0 closures) |
| LNY trough average | $2.1B (66% below baseline) |
| Recovery average | $3.0B (52% below baseline) |
| Every-day names | 617 (active all 16 sessions) |
| Mon/Tue ratio | 2.3x (weekend order accumulation) |

## The Four Phases

| Phase | Dates | Sessions | What Happened |
|-------|-------|----------|---------------|
| **Baseline** | Feb 2–6 | 5 | Normal overnight volume before any Asian closures. Establishes the $6.3B/session benchmark. |
| **Pre-Holiday** | Feb 9–13 | 5 | Anticipatory decay as Asian participants begin reducing activity ahead of LNY. Volume drops 49% with zero Asian markets closed yet. |
| **LNY Holiday** | Feb 17–20 | 4 | Peak closures (CN, TW, KR, HK, SG, VN). Volume hits trough at $2.1B — 66% below baseline. Demonstrates that Asian demand is a structural component of overnight flow, not marginal. |
| **Recovery** | Feb 23–24 | 2 | Markets reopen. Volume rebounds to $3.0B but remains 52% below baseline — recovery is not instantaneous. |

## Dashboard Sections

The single-page dashboard includes:

- **Aggregate Volume Timeline** — bar chart showing all 16 sessions color-coded by phase
- - **Session Calendar** — date, day-of-week, phase tag, volume, and which Asian markets were closed
  - - **Day-of-Week Baseline** — horizontal bars showing Monday through Friday baseline averages
    - - **Sector Decomposition** — which sectors disappeared during closures and which persisted
      - - **Narrative Insights** — auto-generated analysis of patterns (Monday accumulation, anticipatory decay confirmation)
       
        - ## Key Findings
       
        - The analysis demonstrates that Asian participation in overnight U.S. equity trading is not marginal — it is structural. The anticipatory decay pattern (volume dropping before any Asian markets actually close) suggests that participant behavior adjusts in advance, not just in response to closures. The 2.3x Monday/Tuesday ratio confirms weekend order accumulation as a persistent feature of overnight flow.
       
        - ## Architecture
       
        - Single static HTML file (`index.html`) with embedded data and Chart.js visualizations. Deployed via GitHub Pages. No backend, no authentication.
       
        - ## Related Repositories
       
        - | Repo | Purpose |
        - |------|---------|
        - | [sapinover-overnight-dashboard](https://github.com/ejcacciatore/sapinover-overnight-dashboard) | Primary research dashboard — 84 trading days, full microstructure analysis |
        - | [Sapinover_Overnight_Data](https://github.com/ejcacciatore/Sapinover_Overnight_Data) | Research library — Korean retail market analysis, supporting datasets |
        - | [sapinover-overnight-alpha](https://github.com/ejcacciatore/sapinover-overnight-alpha) | U.S. equity trading venue database |
        - | [sapinover-project](https://github.com/ejcacciatore/sapinover-project) | Main Sapinover platform (Next.js 14 on Vercel) |
       
        - ---

        Sapinover LLC · [sapinover-project.vercel.app](https://sapinover-project.vercel.app) · Forward Thinking, Transparent Actions
