+++
date = 2025-05-15T00:00:00  # Schedule page publish date.

title = "Conformal Statistical Inference: A Tutorial for Biostatistics and Machine Learning Applications"
time_start = 2025-05-15
#time_end = 2030-06-01T15:00:00
abstract = "Conformal inference (conformal prediction) is a flexible and distribution-free framework for constructing prediction sets with finite-sample coverage guarantees. This tutorial covers split conformal prediction (SCP), conformal quantile regression (CQR), full conformal, and Jackknife+ methods, with implementations in R and Python. Designed for a biostatistics master's level audience, the tutorial bridges theoretical foundations with practical applications in medical prediction modeling, providing reproducible code and interactive visualizations."
abstract_short = "Comprehensive tutorial on conformal prediction for uncertainty quantification — theory, methods, and reproducible implementations in R and Python."
event = "Department of Statistics and Operations Research Seminar, University of Granada, Spain"
event_url = "https://migariane.github.io/ConformalPrediction_Tutorial_ES.html"
location = "Granada, Spain"

# Is this a selected talk? (true/false)
selected = true

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["Conformal"]

# Links (optional).
url_pdf = ""
url_slides = "https://migariane.github.io/ConformalPrediction_Tutorial_ES.html"
url_video = ""
url_code = "https://github.com/migariane/migariane.github.io"

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""

+++

This tutorial introduces **Conformal Statistical Inference** — a distribution-free framework for constructing prediction sets with valid finite-sample coverage guarantees. It covers:

- **Foundations**: exchangeability, nonconformity scores, coverage probability guarantees
- **Split Conformal Prediction (SCP)**: computationally efficient, data-splitting approach
- **Conformal Quantile Regression (CQR)**: adaptive intervals handling heteroscedasticity
- **Full Conformal Prediction**: exhaustive leave-one-out calibration
- **Jackknife+**: conservative leave-one-out conformal with improved properties

## Resources

- 🎓 **Tutorial Slides (Spanish):** [Quarto RevealJS slides](https://migariane.github.io/ConformalPrediction_Tutorial_ES.html)
- 📘 **Comprehensive Guide (English):** [Interactive notebook](https://migariane.github.io/ConformalInferenceExplained.html)
- 💻 **Reproducible code** available on [GitHub](https://github.com/migariane/migariane.github.io)
