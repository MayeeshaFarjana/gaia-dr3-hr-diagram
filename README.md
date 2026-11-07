# 🌌 Gaia DR3 Hertzsprung–Russell Diagram

Exploring stellar populations through Gaia DR3 astrometric and photometric data.

This beginner-friendly project builds an HR diagram from real observations:
retrieve stars from the Gaia archive, filter unreliable parallaxes, calculate
absolute magnitudes and colour indices, and identify the main sequence, red
giant branch and white dwarf region.

**Stack:** Astropy · Astroquery · Pandas · NumPy · Matplotlib

## Quick start
pip install astropy astroquery pandas numpy matplotlib jupyter
jupyter notebook gaia_dr3_hr_diagram.ipynb

## Data
Gaia DR3 (ESA), queried live through the Gaia archive. No downloads needed.
Data © ESA/Gaia/DPAC.
