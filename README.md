"""
XRD Voigt peak fitting for κ/β/α-Ga₂O₃ epitaxial films
Paper: Deciphering three‑phase competition of Ga₂O₃ on c‑plane sapphire by XRD
Journal: Crystal Growth & Design (CGD)
Author: Zhao Zhang
Date: 2026
Description:
    This script loads raw XRD txt data, performs multi-peak Voigt fitting,
    calculates phase fraction, GPR, BRR, Algorithm results
    exports fitted figures (1200 dpi PNG + vector PDF) and summary table (CSV).
Raw XRD data: txt files stored in folder "xrd_data/"
Output: Figures and CSV summary table saved in folder "DATA/"

Dependencies:
    numpy, pandas, matplotlib, lmfit, scipy
> requirements.txt
numpy>=1.23
pandas>=1.4
matplotlib>=3.5
lmfit>=1.0
scipy>=1.9

License: MIT
