+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = "2016-04-20T00:00:00"

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Teaching"
subtitle = ""

# Order that this section will appear in.
weight = 60

+++

I am an Associate Professor of Biostatistics at the University of Granada (Department of Statistics and Operations Research) and a Distance Learning Module Organizer for the MSc in Epidemiology at the LSHTM.

## Courses

- **EPM304** — Advanced Statistical Methods in Epidemiology (LSHTM)
- **Short Course: Introduction to Survival Analysis in Cancer Epidemiology** — [GitHub repo](https://github.com/migariane/SVA-ULB)
- **Introduction to Causal Inference and the Potential Outcomes Framework** — [Course site](https://ccci.netlify.app/)
- **Computational Causal Inference and Estimation using Stata** (LSHTM) — [Tutorial](/tutorials/CIM.html)

## Tutorials & Open-Access Materials

### 🎓 Featured: Conformal Statistical Inference
Comprehensive tutorials from theory to practice — marginal coverage guarantees, split conformal prediction (SCP), conformal quantile regression (CQR), full conformal, and Jackknife+.

- **[Comprehensive Guide (EN)](/tutorials/ConformalInferenceExplained.html)** — Interactive notebook covering theory and implementation
- **[Tutorial Slides (ES)](/tutorials/ConformalPrediction_Tutorial_ES.html)** — Structured lecture slides in Spanish (NEW)

### Causal Inference & TMLE

- **[TMLE in practice with R](/tutorials/TMLE.nb.html)** — Step-by-step TMLE implementation with influence functions, fluctuation steps, and variance estimation
- **[Applied Computational Causal Inference using Stata](/tutorials/CIM.html)** — Doubly robust methods, AIPW, and TMLE in Stata using the `eltmle` command
- **[Las matemáticas detrás de TMLE (ES)](/tutorials/Maths_TMLE-IF.html)** — Mathematical derivation of TMLE in Spanish: influence functions, semiparametric theory
- **[Delta Method Tutorial](/tutorials/DeltaMethodEpiTutorial.nb.html)** — Variance estimation using the delta method for epidemiological estimands (R notebook)
- **[ELTMLE: One Simulation](/tutorials/eltmle_one_sim.html)** — Stata simulation comparing `eltmle` vs competitors (2017 SUGM)

### Survival Analysis

- **[Introduction to Time-to-Event Analysis](/tutorials/Tutorial-SVA-ULB.html)** — Kaplan-Meier, log-rank tests, and Cox models (ULB workshop)
- **[Net Survival: Cohort Analysis](/tutorials/Cohort.html)** — Standardization of net survival under the relative survival framework (Stata)
- **[Net Survival: STRS & Poisson Regression](/tutorials/TutorialOne.html)** — Modeling net survival using STRS and Poisson regression (Stata)
- **[Net Survival: Flexible Parametric Modeling](/tutorials/TutorialTwo.html)** — Royston-Parmar flexible parametric survival models (Stata)
- **[Competing Risks Analysis](/tutorials/Crisk.html)** — Cumulative incidence functions, cause-specific hazards, and Fine-Gray models (R)

### Machine Learning

- **[Cross-Validation in Practice with R](/tutorials/CrossValidation.nb.html)** — K-fold CV, LOOCV, and bootstrap resampling for model selection

## Interactive Shiny Apps

- [Parametric Survival Distributions](https://watzile.shinyapps.io/miguel_angel_luque_fernandez/)
- [Colliders in Epidemiology](https://watzile.shinyapps.io/EpiCollider/)
- [Expected Date of Delivery](https://watzile.shinyapps.io/dateofdelivery__/)
- [Cancer Comorbidities Network](http://watzilei.com/shiny/CoMCoR/)

## Stata Packages

- **[eltmle](https://github.com/migariane/meltmle)** — Targeted Maximum Likelihood Estimation for the ATE with SuperLearner integration
- **[cvAUROC](https://github.com/migariane/cvAUROC)** — Cross-validated AUC with bootstrap confidence intervals
- **[cmatch](https://github.com/migariane/cmatch)** — Tabulation of matched pairs in 1:1 matched case-control studies

## R Packages & Books

- **[Mathematical Statistics with R](https://github.com/migariane/MatematicaEstadisticaMedicinaR)** — An open-access textbook on mathematical statistics with R (Quarto)
- **[BioEstatR](https://github.com/migariane/BioEstatR)** — R package for classical biostatistics applied to health sciences
- **[Bioestadistica Aplicada](https://migariane.github.io/Bioestadistica/)** — Aplicaciones de bioestadistica para analisis de estudios epidemiologicos (ES)

## Tools & Guides

- **[Claude Code en Windows](/tutorials/claude-code-windows-tutorial.html)** — Guia paso a paso para instalar y usar Claude Code en Windows, orientada a estadisticos (ES)

---

📚 **All tutorials:** [Browse all](/tutorials/)
