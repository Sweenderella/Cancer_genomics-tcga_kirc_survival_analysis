# Cancer_genomics-tcga_kirc_survival_analysis

## Project Overview

Cancer Genomics: Survival analysis of immune and inflammation-related gene expression in TCGA-KIRC

This project investigates whether immune- and inflammation-related gene expression in clear cell renal cell carcinoma (ccRCC) provides information about overall survival beyond standard clinical variables.

## Research question

Does immune- and inflammation-related gene expression add prognostic information for overall survival beyond patient age, sex, pathological tumor stage, and tumor grade in TCGA-KIRC?

## Primary dataset

TCGA-KIRC — The Cancer Genome Atlas Kidney Renal Clear Cell Carcinoma cohort

The primary analysis will use tumor gene-expression and clinical data from patients with clear cell renal cell carcinoma.

Data sources:

- [NCI Cancer Genome Atlas Program](https://www.cancer.gov/ccg/research/genome-sequencing/tcga)
- [Genomic Data Commons (GDC) Data Portal](https://portal.gdc.cancer.gov/)
- [UCSC Xena](https://xena.ucsc.edu/)

## Reproducible external validation
Selected findings will be assessed in the independent E-MTAB-1980 ccRCC cohort. This cohort uses a different gene-expression platform, allowing us to assess whether the direction of a finding is reproducible.

## Repository structure

```text
data/
├── raw/          # Original downloaded dataset;
├── processed/    # Cleaned analysis-ready datasey;
└── external/     # External-validation dataset;

docs/             # Report, documentation and analysis
notebooks/        # python scripts code
results/
├── figures/      # analysis figures
├── models/       # Model outputs
└── tables/       # Results

src/              # Reusable python functions