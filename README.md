# thesis-ai-recruitment

Supporting materials for the thesis:

**University Students’ Perceptions of AI-Based Recruitment Systems: Fairness, Transparency, and Willingness to Apply**

This repository contains the survey instrument, dataset files, and the full Jupyter notebook workflow used to generate the results reported in the thesis.

---

## Folder overview

- **data/**
  - Survey dataset files used for analysis (e.g., `data.csv`).

- **notebooks/**
  - Jupyter notebooks used for Chapter 4 (Results) analyses.

- **notebooks-pdf/**
  - PDF exports of the Jupyter notebooks (for quick viewing without running code).

- **survey-template/**
  - Static copy of the survey instrument (form template).

---

## Notebooks

1. **01-results-data-prep.ipynb**  
   Loads `data.csv` and produces participant profile tables/plots (demographics, education, experience, AI awareness).

2. **02-perception-percentages-blackbox-discrimination.ipynb**  
   Computes and visualizes the % agreeing that AI hiring feels like a “black box” and the % fearing discrimination.

3. **03-cronbach-alpha.ipynb**  
   Calculates Cronbach’s alpha for the main multi-item constructs (after reverse-coding).

4. **04-correlation-analysis.ipynb**  
   Calculates construct scores and runs Pearson correlations (r, p-values) among constructs.

5. **05-construct-descriptives-and-preferences.ipynb**  
   Reports construct means/SDs, key item indicators, and recruitment process preference distributions.

---

## Coding notes (summary)

- Likert agreement items are coded: **1 = Strongly disagree … 5 = Strongly agree**
- Negatively worded items are reverse-coded: **reverse score = 6 - original score**
- Construct scores are computed as mean composites of their corresponding items.

---

## Reproducing the analysis

1. Install Python (recommended: 3.10+).
2. Install packages used in the notebooks: `pandas`, `numpy`, `matplotlib`, `scipy`.
3. Run the notebooks.

---

## Data availability

This repository provides the instrument and analysis workflow; anonymized data are included only where sharing is ethically permitted.
