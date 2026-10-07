# Gamma-Ray Calibration & Compton Scattering

**Charles Beck · UCLA Nuclear Physics Laboratory · Lab 4, June 2026**

The laboratory course ran from April to June 2026. This project analyzes gamma-ray detector measurements and coincidence data to investigate detector calibration and Compton scattering.

## Analysis workflow

- Load and filter detector measurements with pandas and NumPy.
- Explore spectra and detector coincidences using histograms and density scatterplots.
- Fit spectral peaks with Gaussian models using SciPy.
- Estimate energy calibration parameters and inspect residuals.
- Fit two-dimensional coincidence distributions and compare extracted energies with Compton-scattering predictions and expected energy sums.

The notebook uses four detector channels: Fixed, Abel, Baker, and Cain. Calibration measurements include barium, cobalt, cesium, and sodium sources.

## My contribution

I performed the analysis and visualization work using my own code and instructor-provided starter material. The Lab 4 measurements were collected by the teaching assistants over approximately one week.

## Materials

[View the Lab 4 notebook](lab4_gamma_ray_analysis.ipynb).

The current notebook includes saved plots and fit outputs. Its original measurement files and a supporting angle screenshot are not included in this repository. The analysis uses Google Colab `/content/` paths and requires those inputs to run from start to finish.

**Tools:** Python, pandas, NumPy, Matplotlib, SciPy, and Jupyter/Google Colab.

## Interpretation and limitations

This is an exploratory laboratory analysis with detector and calibration limitations:

- Baker had a known issue during data collection.
- Abel required a different filtering approach. The notebook explores a quadratic calibration for Abel, while later energy-conversion cells use linear calibration constants.
- Peak assignments and some reconstructed energy sums need further checking before drawing precise conclusions about agreement with theory.
- The final momentum-calibration section is a template awaiting its experimental input, rather than a completed measurement.

The saved figures document the analysis performed; they are not presented as a precise experimental confirmation of the theoretical curves.

[Back to the portfolio](../../README.md)
