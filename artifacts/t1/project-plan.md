# T1 Project Plan

## Project Goal

Develop a clear and reproducible research workflow for comparing three familiar asset classes represented by one ETF each: SPY (US equities), TLT (long-term US Treasury bonds), and GLD (gold). T1 establishes the written plan; later Finance × AI tutorials are planned to reuse the same repository for a bounded, verifiable agent analysis.

## Available Data

- `data/etf_snapshot.csv` — three rows (SPY, TLT, GLD) with columns `ticker`, `asset_class`, `expected_return_pct`, `volatility_pct`, `max_drawdown_pct`, and `expense_ratio_pct`.
- `data/data_dictionary.md` — field definitions, units, and stated limitations.
- The dataset is synthetic teaching data: all numeric values are illustrative assumptions, not live or historical market observations, and must not be used as investment advice.

## Expected Final Deliverable

A concise, written project plan (`artifacts/t1/project-plan.md`) that documents the goal, inputs, milestones, and limitations. For later tutorials, the planned outcome is an agent-assisted analysis (for example, drawdown and expense-ratio comparisons in T2) with a verified report saved in the repository; those analyses are planned future work, not completed here.

## Three Project Milestones

1. **T1 — Project setup and initial plan (current):** Read the repository overview and data dictionary, write this plan, and save it with Git.
2. **T2 — Bounded agent analysis (planned):** Use an Agent to inspect instructor-prepared inputs, run a small local calculation, verify the result, and save a report without data collection during class.
3. **T3 — Portfolio research starter (planned):** Extend the same repository with a portfolio-level research task and task brief, following the workflow established in T1 and T2.

## One Data Limitation

All values in `etf_snapshot.csv` are synthetic teaching assumptions; the dataset also omits correlations, taxes, transaction costs, liquidity, currency exposure, and investor-specific constraints, so it cannot support real investment decisions.

## Next Action

Review this plan for correctness and consistency with the repository, then save it with Git as instructed during T1. No further analysis is claimed at this stage; the next substantive step is the planned T2 analysis task using the instructor-prepared daily price data.