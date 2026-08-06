# LEANER Fasting Study

Analysis pipeline for the **LEANER** randomized controlled trial investigating the effects of a 5-day prolonged fasting intervention on healthy adults.

This repository contains the analysis scripts used for the processing and statistical evaluation of clinical, microbiome, and metabolomics data generated during the study.

**Project status:**  Under revision 

---

## Study overview

The LEANER study investigated the short- and long-term effects of a 5-day fasting intervention in healthy adults.

Main outcomes included:

- Body composition
- Clinical parameters
- Gut microbiome composition
- Plasma metabolomics
- Fecal metabolomics

In addition, baseline microbiome and clinical variables were used to develop machine learning models predicting long-term weight-loss response.

---

## Study design

- Randomized, waitlist-controlled intervention study
- 38 healthy participants
- 5-day fasting intervention
- 12-week follow-up
- ClinicalTrials.gov: **NCT04452916**

---

## Repository structure

```
src/            Analysis scripts
data/           Input data
figures/        Final figures
results/        Output tables and plots
docs/           Project documentation
logs/           Session information and logs
```

---

## Analysis workflow

1. Import and preprocess data
2. Clinical data analysis
3. Microbiome analysis
4. Metabolomics analysis
5. Multi-omics integration
6. Machine learning
7. Figure generation

---

## Data availability

The datasets associated with this study are available via **Zenodo**.

doi: https://doi.org/10.5281/zenodo.17493808). 

---

## Publication

**Title:** *Machine Learning Identifies Microbiome and Clinical Predictors of Sustained Weight Loss Following Prolonged Fasting*

**Status:** Under revision



---

## Software

This project uses

- R
- Quarto
- renv (package version management)

The computational environment can be restored using

```r
renv::restore()
```

---

## Author

Gelsomina Kaufhold
