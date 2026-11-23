# Physics-Based Modeling & Monte Carlo Uncertainty Analysis of the 2010 Mount Merapi Rapid Lava Dome Extrusion

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24465743.svg)](https://doi.org/10.5281/zenodo.24465743)

## Overview
This repository contains the fully reproducible Python Jupyter Notebook, technical report, and presentation deck for a continuum mechanics and probabilistic study of the 1–4 November 2010 rapid lava dome extrusion at Mount Merapi, Indonesia.

## Repository Contents
- `Merapi_2010_Conduit_Flow_MonteCarlo.ipynb` — Full Python simulation (1D mass conservation, Hagen–Poiseuille momentum balance, thermal/Stefan solidification, and 20,000-sample Monte Carlo uncertainty analysis).
- `Merapi_2010_Portfolio_Report.pdf` — Complete technical report.
- `Merapi_2010_Portfolio_Deck.pptx` — Executive presentation slides.

## How to Run
```bash
pip install numpy scipy matplotlib pandas
jupyter notebook Merapi_2010_Conduit_Flow_MonteCarlo.ipynb
```

## Citation
If you use this code or report, please cite the Zenodo archive:
> Oktafiandariento, T. S. (2026). *Physics-Based Modeling & Monte Carlo Uncertainty Analysis of the 2010 Mount Merapi Rapid Lava Dome Extrusion* (v1.0.0). Zenodo. https://doi.org/10.5281/zenodo.19201465