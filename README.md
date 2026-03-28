# educacion-media-unsupervised

This repository contains the code and data used for the unsupervised analysis of Paraguay's educational data.

## Description
The project includes:
- preprocessing of educational territorial data
- dimensionality reduction with UMAP
- clustering with HDBSCAN
- anomaly detection with LOF

## Repository structure
- `data/processed/`: processed data used in the experiments
- `notebooks/`: Jupyter notebook for the analysis
- `outputs/figures/`: generated figures
- `outputs/tables/`: generated tables
- `src/`: support scripts

## Requirements
Install dependencies with:

```bash
pip install -r requirements.txt
## Main files
- `data/processed/matriculaciones_departamentos_distritos_20260120.csv`
- `notebooks/Identificacion_patrones_MEC_organizado_github.ipynb`

## Reproducibility
This repository includes the processed dataset, notebook, and generated figures needed to reproduce the main analysis presented in the study.

## License
MIT
