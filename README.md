# Microenvironmental Niches in Reversible versus Progressive Lung Fibrosis

## Abstract
This repository contains the analysis code and data for our study on microenvironmental niches that dictate divergent fibroblast fates in reversible versus progressive lung fibrosis.

## Key Findings
- 🔬 First spatial transcriptomic comparison across ILD spectrum
- ⚡ Discovery of B cell-MIF-CD74 signaling axis
- 🎯 Glucocorticoid responsiveness prediction model
- 💡 Novel "niche determinism" theory of fibrosis

## Code Structure
- `code/01_data_preprocessing/`: Raw data processing and quality control
- `code/02_spatial_analysis/`: Spatial transcriptomics analysis
- `code/03_integration_analysis/`: Spatial-scRNA integration
- `code/04_functional_analysis/`: Pathway and functional analysis
- `code/05_visualization/`: Plot generation scripts
- `code/06_validation/`: Validation experiments

## Requirements
- R >= 4.0.0
- Seurat >= 4.0
- Spatial packages (Visium, etc.)

## Usage
```bash
# Clone the repository
git clone https://github.com/songlicheng666/Microenvironmental-Niches-in-Reversible-versus-Progressive-Lung-Fibrosis.git

# Run analysis pipeline
Rscript code/run_analysis.R
