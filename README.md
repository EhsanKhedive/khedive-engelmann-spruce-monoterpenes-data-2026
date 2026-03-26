# khedive-engelmann-spruce-monoterpenes-data-2026

This repository contains the dataset and R Markdown scripts used for the analysis in the paper:

**“Climate indirectly modulates tree survival of spruce beetle attacks via effects on constitutive and induced secondary metabolites”**  

## Repository contents

- `Monoterpenes.csv` – Raw dataset of GC/MS peak areas for monoterpenes used in the analysis
- `Site_climate.csv` – Climate data for the studied sites
- `Standards.csv` – Monoterpene standards dataset to set calibration curves and convert peak areas to concentration
- `Analysis code.Rmd` – R Markdown file that reproduces the figures and supplementary materials    
- `README.md` – This file  

## Usage

1. Put the datasets along with `Analysis code.Rmd` in the same folder
2. Open `Analysis code.Rmd` in RStudio
3. set the current folder as working directory in lines 37 and 306 (replace the address with the three dots)
4. Knit the R Markdown file to produce all figures, tables, and supplementary materials  
5. Ensure all required R packages are installed 

## Data availability and license

- **Data license:** CC-BY 4.0  
- **Code license:** MIT  
- Archived and citable version (v1.0) available via Zenodo: 10.5281/zenodo.19225955

## Citation

If you use this dataset or code, please cite:

Khedive, E., Fathi Moghanloo, S., Davis, T.S. (2026). *Spruce monoterpenes dataset and R Markdown scripts.* Zenodo. DOI: 10.5281/zenodo.19225955
