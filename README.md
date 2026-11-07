# 🌌 Gaia DR3 Hertzsprung–Russell Diagram

Exploring Stellar Populations Through Gaia DR3 Astrometric and Photometric Data

In this project, I used real observations from the Gaia DR3 catalogue to
build a Hertzsprung–Russell diagram and study how stars are distributed
across different evolutionary stages.

## What I did
- Retrieved a random sample of stars from the Gaia archive using ADQL
- Filtered out unreliable parallax measurements (parallax/error and RUWE cuts)
- Calculated distances and absolute magnitudes with Astropy
- Computed BP−RP colour indices
- Constructed the HR diagram
- Identified the main sequence, red giant branch and white dwarf region
- Compared my sample with a volume-limited 100 pc sample to examine selection effects

## Tools
Astropy · Astroquery · Pandas · NumPy · Matplotlib

## Run it
pip install astropy astroquery pandas numpy matplotlib jupyter
jupyter notebook gaia_dr3_hr_diagram.ipynb

## What I learned
Population fractions depend heavily on how a sample is selected. Luminous
giants are visible far away, while faint white dwarfs only appear in nearby
volumes.

## Data
Gaia DR3 (ESA), accessed through the Gaia archive.
Data © ESA/Gaia/DPAC.
