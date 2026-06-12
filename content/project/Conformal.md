+++
# Date this page was created.
date = "2025-06-01"

# Project title.
title = "Conformal Statistical Inference: From Theory to Practice"

# Project summary to display on homepage.
summary = "Comprehensive tutorial on conformal inference covering split conformal prediction (SCP), conformal quantile regression (CQR), full conformal, and Jackknife+. Includes interactive notebooks in English and structured lecture slides in Spanish with full implementation details."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = ""

# Tags: can be used for filtering projects.
tags = ["conformal", "machine-learning", "tutorial"]

# Optional external URL for project (replaces project detail page).
external_link = "https://migariane.github.io/ConformalInferenceExplained.html"

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

Conformal inference (also known as conformal prediction) is a flexible and distribution-free framework for constructing prediction sets with finite-sample coverage guarantees. This tutorial provides a comprehensive introduction that bridges theory and practice.

## What's Covered

- **Foundations of Conformal Inference** — exchangeability, nonconformity scores, and coverage guarantees
- **Split Conformal Prediction (SCP)** — the computationally efficient workhorse method
- **Conformal Quantile Regression (CQR)** — adaptive prediction intervals handling heteroscedasticity
- **Full Conformal Prediction** — using all data for calibration (computationally intensive but theoretically optimal)
- **Jackknife+** — leave-one-out conformal with improved coverage properties

## Resources

- 📘 **Comprehensive Guide (English):** [Interactive HTML notebook](https://migariane.github.io/ConformalInferenceExplained.html)
- 🎓 **Tutorial Slides (Spanish):** [Quarto RevealJS presentation](https://migariane.github.io/ConformalPrediction_Tutorial_ES.html)
- 💻 **Source Code:** Available in the [tutorial repository](https://github.com/migariane/migariane.github.io)

## Implementation

All methods are implemented with reproducible code in R and Python, with detailed explanations of each algorithm step. The tutorial slides in Spanish are designed for a biostatistics master's level audience at the University of Granada.

**Keywords:** Conformal inference, conformal prediction, prediction intervals, uncertainty quantification, distribution-free inference, machine learning, statistical learning theory.
