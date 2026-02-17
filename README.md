# Measure Theory Lab

Interactive Jupyter notebooks illustrating key concepts in measure theory, probability theory, stochastic processes, and their applications to finance — through computation and visualization.

## Setup

```bash
pip install -r requirements.txt
jupyter notebook
```

## Table of Contents

### Measure Theory Foundations

| # | Topic | Notebook |
|---|-------|----------|
| 1 | **Vitali Set Construction** — Why non-measurable sets exist and why we need sigma-algebras | [01_vitali_set.ipynb](notebooks/foundations/01_vitali_set.ipynb) |
| 2 | **Cantor Set & Devil's Staircase** — A measure-zero uncountable set and its singular continuous CDF | [02_cantor_set.ipynb](notebooks/foundations/02_cantor_set.ipynb) |
| 3 | **Fat Cantor Sets** — Nowhere-dense sets with positive measure, showing measure and topology are independent | [03_fat_cantor_sets.ipynb](notebooks/foundations/03_fat_cantor_sets.ipynb) |
| 4 | **Borel-Cantelli Lemma** — When infinitely many events occur (or don't) | [04_borel_cantelli.ipynb](notebooks/foundations/04_borel_cantelli.ipynb) |

### Convergence Concepts

| # | Topic | Notebook |
|---|-------|----------|
| 5 | **Convergence Mode Separation** — Sequences that converge in one sense but not another (typewriter sequence, etc.) | [05_convergence_modes.ipynb](notebooks/convergence/05_convergence_modes.ipynb) |
| 6 | **Egoroff's Theorem** — How a.e. convergence becomes uniform after removing a small set | [06_egoroff_theorem.ipynb](notebooks/convergence/06_egoroff_theorem.ipynb) |

### Probability Theory

| # | Topic | Notebook |
|---|-------|----------|
| 7 | **Strong Law of Large Numbers** — Almost sure convergence of sample means | [07_strong_law.ipynb](notebooks/probability/07_strong_law.ipynb) |
| 8 | **Central Limit Theorem** — Universality of the Gaussian via normalized sums | [08_clt.ipynb](notebooks/probability/08_clt.ipynb) |
| 9 | **Law of the Iterated Logarithm** — The exact fluctuation envelope of random walks | [09_law_iterated_logarithm.ipynb](notebooks/probability/09_law_iterated_logarithm.ipynb) |
| 10 | **Martingale Convergence** — Almost sure convergence of martingales (Polya urn, branching processes) | [10_martingale_convergence.ipynb](notebooks/probability/10_martingale_convergence.ipynb) |

### Integration & Differentiation

| # | Topic | Notebook |
|---|-------|----------|
| 11 | **Lebesgue vs. Riemann Integration** — Functions integrable in one sense but not the other | [11_lebesgue_vs_riemann.ipynb](notebooks/integration/11_lebesgue_vs_riemann.ipynb) |
| 12 | **Convergence Theorems (MCT & DCT)** — When limits and integrals commute, and when they don't | [12_convergence_theorems.ipynb](notebooks/integration/12_convergence_theorems.ipynb) |
| 13 | **Radon-Nikodym Derivatives** — Describing one measure relative to another via densities | [13_radon_nikodym.ipynb](notebooks/integration/13_radon_nikodym.ipynb) |

### Geometric & Advanced

| # | Topic | Notebook |
|---|-------|----------|
| 14 | **Hausdorff Dimension** — Non-integer dimensions of fractals via box-counting | [14_hausdorff_dimension.ipynb](notebooks/geometric/14_hausdorff_dimension.ipynb) |
| 15 | **Buffon's Needle** — Estimating pi through geometric probability | [15_buffon_needle.ipynb](notebooks/geometric/15_buffon_needle.ipynb) |
| 16 | **Concentration Inequalities** — Markov, Chebyshev, Chernoff & Hoeffding bounds vs. empirical tails | [16_concentration_inequalities.ipynb](notebooks/geometric/16_concentration_inequalities.ipynb) |

### Brownian Motion

| # | Topic | Notebook |
|---|-------|----------|
| 17 | **Brownian Motion Construction** — Random walk scaling limits, Donsker's theorem, and sample path visualization | [17_brownian_motion_construction.ipynb](notebooks/brownian_motion/17_brownian_motion_construction.ipynb) |
| 18 | **Brownian Motion Properties** — Continuity, nowhere differentiability, quadratic variation, self-similarity, and reflection | [18_brownian_motion_properties.ipynb](notebooks/brownian_motion/18_brownian_motion_properties.ipynb) |
| 19 | **Stochastic Integration Intro** — Ito integral via Riemann sums, Ito's formula, and geometric Brownian motion | [19_stochastic_integration_intro.ipynb](notebooks/brownian_motion/19_stochastic_integration_intro.ipynb) |

### Conditional Expectation

| # | Topic | Notebook |
|---|-------|----------|
| 20 | **Conditional Expectation** — Definition as L² projection, tower property, and visualization as smoothing | [20_conditional_expectation.ipynb](notebooks/conditional_expectation/20_conditional_expectation.ipynb) |
| 21 | **Martingale Theory Deep Dive** — Filtrations, optional stopping, Doob decomposition, and maximal inequalities | [21_martingale_theory_deep_dive.ipynb](notebooks/conditional_expectation/21_martingale_theory_deep_dive.ipynb) |

### Applications to Finance

| # | Topic | Notebook |
|---|-------|----------|
| 22 | **Risk-Neutral Measure** — Binomial model, replication, and the fundamental theorem of asset pricing | [22_risk_neutral_measure.ipynb](notebooks/applications_to_finance/22_risk_neutral_measure.ipynb) |
| 23 | **Girsanov Theorem** — Change of drift via change of measure, likelihood ratio process, and P-to-Q connection | [23_girsanov_theorem.ipynb](notebooks/applications_to_finance/23_girsanov_theorem.ipynb) |
| 24 | **Option Pricing Foundations** — Black-Scholes via risk-neutral expectation, Monte Carlo under Q, and Greeks | [24_option_pricing_foundations.ipynb](notebooks/applications_to_finance/24_option_pricing_foundations.ipynb) |
