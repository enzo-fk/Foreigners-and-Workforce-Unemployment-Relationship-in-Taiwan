# Foreigners-and-Workforce-Unemployment-Relationship-in-Taiwan
First Real World Data Science Case Study and Project
PDF file attached for details

Project Timeline:
1.Initial Exploratory Project
  Gathered monthly data on the foreign-worker share and the unemployment rate to see the raw trend.

2.Pilot Hypothesis Test
  Null H₀: “More foreign workers raise unemployment.”
  Result: Significant inverse correlation ⇒ H₀ rejected; the alternative gained support.

3.Full Multivariate-Analysis (MVA) Project
  Added GDP growth, inflation, interest rate, FDI, labour-force metrics; used PCA/FA → k-Means/LDA → CCA → robust regression to isolate effects.

4.Comprehensive Findings
  Macro levers dominate unemployment variation; foreign-worker share still shows a small but consistent negative coefficient (≈ –0.07 ppt per +1 ppt FW %).
  Policy takeaway: macro stabilisation and up-skilling beat blanket labour caps.

5.Future Work (Next Phase)

Dynamic causality: move to VECM/Bayesian VAR to capture lags between foreign-labour inflow and jobless changes.

Sector & regional drill-down: build a two-digit NAICS panel (or county-level data) to see where any crowd-out might still exist.

Wage dimension: merge in average hourly earnings to test whether foreign labour affects pay, not just head-counts.

Natural-experiment design: exploit quota adjustments or sudden policy shocks (e.g., 2017 hiring-fee reform) for causal identification via diff-in-diff / event study.

Skill-mix analysis: separate blue-collar vs. white-collar foreign hires and examine substitution vs. complementarity with local skill groups.

Forecasting tool: deploy a dashboard that updates unemployment risk as new macro data and foreign-worker numbers arrive.
