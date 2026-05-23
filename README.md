# Calibration of LiF:Mg,Cu,P (MCP) Thermoluminescent Detectors

**Author:** Nigus Alene Assefa  
**Institution:** Institute of Nuclear Physics, Polish Academy of Sciences  
**Supervisors:** dr. hab. Paweł Bilski, Dr. Anna Mrozik  
**Date:** March 2026

## Overview
This repository contains data and analysis from the calibration of MCP thermoluminescent detectors for beta radiation from a Sr-90/Y-90 source.

## Contents
- `MCP_calibration_report.pdf` - Full experimental report
- `raw_data.csv` - Raw TL signals from Harshaw 3500 reader
- `analysis_script.R` - R script for IRF calculation and dose estimation
- `poster.pdf` - Conference poster

## Key Results
- **IRF range:** 0.876 – 1.158 (batch of 80+ detectors)
- **Weak source dose rate:** 0.0385 mGy/s (March 2026)
- **Strong source dose rate:** 61.21 mGy/s (March 2026)
- **Sr-90 half-life:** 28.8 years (2.38% annual decay)

## How to Use
1. Clone this repository
2. Run `analysis_script.R` in RStudio
3. Raw data is in `raw_data.csv`

## Citation
If you use this data, please cite:
> Assefa, N. A. (2026). Calibration of LiF:Mg,Cu,P (MCP) thermoluminescent detectors. IFJ PAN. https://github.com/YOUR_USERNAME/mcp-calibration

## Contact
nigus.assefa@ifj.edu.pl
