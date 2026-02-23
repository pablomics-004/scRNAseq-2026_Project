# Differential Expression Analysis
## Aspergillus fumigatus Infection in Airway Epithelial Cells
### Overview

This project performs a differential gene expression analysis using RNA-seq data from recount3 to investigate the transcriptional response of airway epithelial cells infected with Aspergillus fumigatus conidia.

The report fulfills the course requirements:

- Uses a public recount3 dataset
- Includes `>2` figures
- Performs differential expression analysis
- Provides biological interpretation
- Publicly available repository

### Methods

- Data retrieved using recount3
- Quality control and filtering performed
- Normalization to account for sequencing depth and RNA composition (`edgeR`)
- Differential expression analysis using a statistical model (`limma`)
- FDR correction applied to identify significant genes

### Results

The analysis reveals significant transcriptional changes following infection, including:

- Upregulation of immune and inflammatory response genes
- Activation of host defense pathways
- These results highlight the active role of epithelial cells in antifungal response.

### Reproducibility

Render the report with:

```shell
quarto render Report/SalazarPablo_Report.qmd
```
Required R packages:

- recount3
- edgeR
- limma
- SummarizedExperiment
