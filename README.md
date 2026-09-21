# LEANER Fasting Study

Analysis pipeline for the **LEANER** randomized controlled trial investigating the effects of a 5-day prolonged fasting intervention on healthy adults.

This repository contains the analysis scripts used for the processing and statistical evaluation of clinical, microbiome, and metabolomics data generated during the study.

**Project status:** Published

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

**Title:** *Machine learning identifies microbiome and clinical predictors of sustained weight loss following prolonged fasting*

**Journal:** Genome Medicine, Volume 18, article number 136 (2026)

**Published:** 16 September 2026 (open access)

**DOI:** [10.1186/s13073-026-01765-0](https://doi.org/10.1186/s13073-026-01765-0)

### How to cite

> Kaufhold G, Bartolomaeus TUP, Schütte K, Schütte T, Kamboj S, Löber U, Rahn G, McParland V, Braun L, Markó L, Mammadli M, Krannich A, Bahr LS, Gutmann F, Paul F, Ducarmon QR, Zeller G, Mesnage R, Wilck N, Zernecke A, Oefner PJ, Gronwald W, Müller DN, Forslund-Startceva SK, Bähring S, Bartolomaeus H, Siebert N. Machine learning identifies microbiome and clinical predictors of sustained weight loss following prolonged fasting. *Genome Med*. 2026;18:136. https://doi.org/10.1186/s13073-026-01765-0

```bibtex
@article{Kaufhold2026,
  author  = {Kaufhold, Gelsomina and Bartolomaeus, Theda U. P. and Sch{\"u}tte, Kristin and Sch{\"u}tte, Till and Kamboj, Sakshi and L{\"o}ber, Ulrike and Rahn, Gabriele and McParland, Victoria and Braun, Lena and Mark{\'o}, Lajos and Mammadli, Matanat and Krannich, Alexander and Bahr, Lina S. and Gutmann, Friederike and Paul, Friedemann and Ducarmon, Quinten R. and Zeller, Georg and Mesnage, Robin and Wilck, Nicola and Zernecke, Alma and Oefner, Peter J. and Gronwald, Wolfram and M{\"u}ller, Dominik N. and Forslund-Startceva, Sofia K. and B{\"a}hring, Sylvia and Bartolomaeus, Hendrik and Siebert, Nadja},
  title   = {Machine learning identifies microbiome and clinical predictors of sustained weight loss following prolonged fasting},
  journal = {Genome Medicine},
  year    = {2026},
  volume  = {18},
  number  = {1},
  pages   = {136},
  doi     = {10.1186/s13073-026-01765-0}
}
```



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
