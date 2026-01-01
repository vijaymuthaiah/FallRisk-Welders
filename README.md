# Postural Instability and Fall Risk in Welders  
## An ICF-Informed Approach to Risk Stratification

![Status](https://img.shields.io/badge/status-active-success)
![Language](https://img.shields.io/badge/language-R-blue)
![Methods](https://img.shields.io/badge/methods-PCA%20%7C%20Firth%20Logistic%20%7C%20FAMD-informational)
![License](https://img.shields.io/badge/license-MIT-green)
![Journal](https://img.shields.io/badge/target%20journal-Brain%20Research%20Bulletin-blueviolet)

---

## Overview
This repository contains analysis code and supporting materials for the study:

**Postural Instability and Fall Risk in Welders: An ICF-Informed Approach to Risk Stratification**

Chronic welding exposure is associated with neurotoxic injury and secondary parkinsonism (manganism), yet postural instability and fall risk remain poorly characterized. This study evaluates balance impairment and fall history in welders using a multivariate analytical framework grounded in the **International Classification of Functioning, Disability and Health (ICF)**.

---

## Abstract
**Objective.** Welding exposure is associated with secondary parkinsonism (manganism) and long-term neurological dysfunction, including auditory–vestibular impairment. However, postural instability and fall risk in welders remain understudied. This study aimed to quantify balance impairment and fall risk in welders and to assess whether integrating personal and environmental factors within the ICF framework improves characterization of fall history.

**Methods.** Principal component analysis (PCA) was used to derive latent composite scores for balance performance, occupational exposure, and personal protective equipment (PPE) use. These components were entered into Firth penalized logistic regression models to evaluate associations with fall history while accounting for small-sample bias. Factorial analysis of mixed data (FAMD) was used to integrate continuous and categorical variables and to visualize multivariate structure.

**Results.** Welders demonstrated significantly worse balance and fall-related confidence compared with controls. The full multivariable model incorporating age, balance, exposure, and PPE indices showed the best overall fit, with age emerging as the strongest independent predictor of fall history.

**Conclusion.** Welders exhibit clinically meaningful balance impairments within a multifactorial exposure–health context, supporting ICF-informed, exposure-aware screening and targeted balance interventions.

---

## Repository Structure
welders-fall-risk-icf/
│
├── Code/
│ └── welders1qmdoutput.pdf # Rendered analysis report
│
├── Data/
│ └── wdat1.xlsx # De-identified dataset
│
├── Documents/
│ └── Welders_Manuscript_12_30_2025.docx
│ # Manuscript draft
│
├── Output/
│ ├── Figures.docx # Publication-ready figures
│ └── Tables.docx # Publication-ready tables
│
├── README.md
├── LICENSE
└── CITATION.cff

---

## Analytical Framework
- **Dimensionality reduction:** Principal Component Analysis (PCA)  
- **Fall-risk modeling:** Firth penalized logistic regression  
- **Multivariate integration:** Factorial Analysis of Mixed Data (FAMD)  
- **Conceptual framework:** International Classification of Functioning, Disability and Health (ICF)

---

## Software
Analyses were conducted in **R (≥4.2.0)** using:
- tidyverse
- FactoMineR, factoextra
- logistf
- fastDummies
- tableone, kableExtra
- patchwork

---

## Data Availability
Data are provided in de-identified form and should be used in accordance with institutional, ethical, and IRB guidelines. No personally identifiable information (PHI) is included.

---

## Citation
If you use this repository, please cite the associated manuscript and this codebase.  
Citation metadata are provided in `CITATION.cff`.

---

## Author
**Vijaya Prakash, PhD**  
University at Buffalo, SUNY  
Brain Plasticity & Neurorehabilitation Laboratory

---

## License
This repository is released under the MIT License.
