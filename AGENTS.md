# AGENTS.md

## Purpose
This repository explores Rubik’s Cube mathematics and algorithms using Python, JupyterLab notebooks, and data‑science visualization libraries. This document defines best practices for agents and collaborators working in this repo.

## Project Expectations
- Prefer clear, mathematically grounded explanations and reproducible experiments.
- Optimize for correctness and clarity over cleverness.
- Keep notebooks light, modular, and easy to re-run.

## Repository Standards
- Use Python 3.x and follow PEP 8 style guidelines.
- Prefer type hints for new Python modules.
- Keep functions small and well‑named.
- Add docstrings for public functions or classes.

## JupyterLab & Notebooks
- Use notebooks for exploration and visualization; move stable utilities into `*.py` modules.
- Keep outputs minimal; clear large or noisy outputs before committing.
- Ensure notebooks run top‑to‑bottom without manual intervention.
- Avoid hard‑coded absolute paths; use relative paths under the repo.

## Data & Visualization
- Use standard data‑science libraries (e.g., NumPy, SciPy, pandas, matplotlib, seaborn, plotly) as appropriate.
- Keep visualizations labeled and readable; include titles, axis labels, and legends where relevant.
- Prefer deterministic plots (set seeds when randomness is involved).

## Algorithms & Experiments
- Document assumptions, definitions, and notation clearly.
- When adding new algorithms:
  - Describe the algorithm in markdown with references if applicable.
  - Provide a simple, verifiable test or demonstration.
  - Measure performance only when meaningful and reproducible.

## Testing & Validation
- Add lightweight tests for reusable utilities or algorithms.
- Use small, deterministic test cases where possible.
- Validate invariants (e.g., cube state validity) in helper functions.

## Version Control
- Keep commits focused and descriptive.
- Do not commit large binary artifacts or generated outputs unless explicitly required.

## Tooling
- Favor `rg` for searching.
- Use `apply_patch` for small edits when practical.

## Communication
- Be explicit about assumptions and tradeoffs.
- If a change might impact results or interpretations, call it out.

