# HTS_project: Differential Expression and Functional Analysis of COVID-19 Patients based on Viral Load, Age and Sex
## Wiktoria Brandys, Maria Chmielorz, Julia Kwiecińska, Katarzyna Kuhny

This project performs differential gene expression (DGE) analysis on RNA-seq data from GEO dataset GSE152075, focusing on age group (AGEGR), sex (GENDER), clinical state (STATEGR), and SARS-CoV-2 positivity (POS).

| Factor | Description | Levels |
|--------|-------------|--------|
| **STATEGR** | SARS-CoV-2 Ct value (viral load proxy) | low (>24), medium (19-24), high (<19) |
| **AGEGR** | Age groups | =<60 years, >60 years |
| **GENDER** | Biological sex | Male, Female |
| **POS** | SARS-CoV-2 positivity | Positive samples |

<br>

**The project includes**:
1.  **Data download** RNA-seq data from GEO (GSE152075)
2.  **Preprocessing** and organizing data
3.  **Differential Expression Analysis (DEA)** to identify genes with significantly altered expression between experimental conditions
4.  **Gene selection** based on statistical significance (padj < 0.01, |log2FC| > 2)
5.  **Functional analysis** of differentially expressed genes using **Gene Ontology (GO terms)**

A list of all R packages used in the project, including versions and citations, is available in the file 'packages.txt'.

All source code and detailed descriptions of each analysis step are included in the file 'hts_project.qmd'.
