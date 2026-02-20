# PERT Calculator

A simple, single-page PERT (Program Evaluation and Review Technique) calculator for three-point story estimation in developer days.

**Live site:** [https://drewpureescapes.github.io/pert-calcuator/](https://drewpureescapes.github.io/pert-calcuator/)

## What is PERT?

PERT uses a weighted average of three estimates to produce a more realistic prediction:

- **Optimistic** — best-case scenario
- **Most Likely** — realistic estimate
- **Pessimistic** — worst-case scenario

**PERT Estimate** = (O + 4×M + P) ÷ 6

**Standard Deviation** = (P − O) ÷ 6

## Features

- Three dropdown selectors for Optimistic, Most Likely, and Pessimistic values (0.5 to 30)
- Instant calculation — results update as soon as all three values are selected
- Validation — Most Likely must be ≥ Optimistic, Pessimistic must be ≥ Most Likely
- PERT estimate displayed in Days with standard deviation
- Confidence ranges at 68%, 95%, and 99.7%
- Calculation history saved to localStorage (up to 50 entries)
- Copy result to clipboard
- Responsive design — works on desktop and mobile
- Accessible — semantic HTML, ARIA attributes, keyboard navigation, WCAG AA contrast
- Zero dependencies — single HTML file, no build step

