# Computational Exploration of Aging: Integrating DNA Methylation

## Project Overview
This project explores the biological aging process through computational analysis of DNA methylation data. The work identifies key biomarkers (CpG sites) linked to aging, constructs an epigenetic clock model, and uncovers biological pathways influenced by these epigenetic markers.

## Objectives
- **Identify DNA methylation biomarkers correlated with age.**
- **Model an epigenetic clock using DNA methylation profiles.**
- **Map key CpG sites to genes and explore biological pathways involved in aging.**

## Data Source
- **Dataset:** DNA methylation profiles from the Gene Expression Omnibus (GEO).
- **Platform:** Illumina HumanMethylation450 BeadChip.
- **Samples:** 656 individuals spanning various age ranges.

## Methodology

### Data Preprocessing
- **Initial inspection and cleaning** of methylation beta values.
- **Filtering** of CpG sites based on methylation variability.
- **Cleaning and merging** age metadata with methylation data.

### Correlation Analysis and Biomarker Identification
- **Computed Pearson correlations** between CpG site methylation levels and chronological age.
- **Selected top CpG sites** as biomarkers of biological aging.

### Epigenetic Clock Modeling
- **Built and validated an epigenetic clock model** using LASSO regression.
- **Model performance** evaluated with Mean Absolute Error (MAE) and R-squared (R²).

### Gene Mapping
- **Mapped identified CpG sites to genes** using the minfi package in R with Illumina annotation data.

### Pathway Enrichment Analysis
- **Conducted enrichment analysis** using Enrichr (KEGG 2021 Human pathway database).
- **Identified significant biological pathways** related to aging, including cellular senescence, inflammation, and mitochondrial function.

## Key Findings
- **Discovered biomarkers** significantly correlated with aging.
- **Developed an accurate epigenetic clock model** predicting biological age.
- **Identified critical pathways**, such as those linked to cardiovascular health, mitochondrial function, and chronic inflammation.

## Tools and Technologies
- **Data Analysis:** Python (pandas, NumPy), R (minfi package)
- **Machine Learning:** LASSO regression (scikit-learn)
- **Visualization:** Plotly
- **Pathway Analysis:** Enrichr




