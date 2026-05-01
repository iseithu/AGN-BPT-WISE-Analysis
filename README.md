# SDSS Galaxy Classification: BPT & WISE

This project uses SDSS data to classify galaxies using the BPT diagram and the WISE color–color diagram.

## Overview
- Data selection using SDSS SQL queries  
- BPT diagram for optical classification  
- WISE color–color diagram for infrared classification  
- Comparison between optical and infrared AGN identification  

## Files
- `bpt_q1.csv` → Initial SDSS dataset with emission line fluxes
- `bpt_q1_op.csv` → Dataset including class and subclass information
- `wise_q1.csv` → SDSS–WISE cross-matched dataset for infrared analysis 
- `AGN_BPT_WISE_Analysis.ipynb` → Main analysis notebook  

## Tools Used
- Python (NumPy, Pandas, Matplotlib)  
- SDSS SkyServer SQL  
- Jupyter Notebook  
