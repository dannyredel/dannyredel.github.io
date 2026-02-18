# Blog Post Plan — DiD Series

## Completed

| # | Post | File | Status |
|---|------|------|--------|
| 1 | Interpreting Event Studies Across Modern DiD Methods | `posts/event_study_comparison/event_study_comparison.ipynb` | Done |
| 2 | Five Ways to Improve Your Event Study Plots | `posts/event_study_best_practices/event_study_best_practices.ipynb` | Done |
| 3 | Sensitivity Analysis for Parallel Trends | `posts/parallel_trends_sensitivity/parallel_trends_sensitivity.ipynb` | Done |
| — | SynthDiD post updated with TROP (Athey et al. 2025) | `posts/synthetic_did/synthetic_did.ipynb` | Done |
| — | Project entry for diff-diff contribution | `projects.qmd` | Done |

## Remaining

### Post 4: Standard Errors for DiD (deferred to "later")
- Cluster-robust, heteroskedasticity-robust, bootstrap, Wild Cluster Bootstrap
- Hansen (2025) — "Standard Errors for Difference-in-Difference Regression"
- Reference PDF in `notebooks/J of Applied Econometrics - 2025 - Hansen...pdf`

### Housekeeping
- Cover images needed for all new posts:
  - `posts/event_study_comparison/` (referenced as `event_study_cover.png`)
  - `posts/event_study_best_practices/` (referenced as `best_practices_cover.png`)
  - `posts/parallel_trends_sensitivity/` (referenced as `sensitivity_cover.png`)
  - `assets/cover/diff-diff.png` (project card)

## Exploration Notebooks (source material)
- `notebooks/diff_diff_plotting_exploration.ipynb` — ggfixest gap analysis, `iplot_data()`, `ggiplot()` prototypes
- `notebooks/honest_inference_exploration.ipynb` — sup-t bands, smoothest path, functional SCBs, multi-model fairness

## Python Package (separate project)
- Built at `C:\Users\danny\OneDrive\Profesional\diff-diff-contrib`
- Visualization & honest inference extensions for the diff-diff package
