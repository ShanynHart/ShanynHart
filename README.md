# Shanyn Hart

PhD in physics (University of Cape Town), postdoc in gamma-ray detector development at iThemba LABS, South Africa.

My research work is, at its core, statistical inference on large noisy datasets: extracting signals from digitised detector waveforms, calibrating instruments by nonlinear regression, building and classifying multi-million-event coincidence datasets, and validating measurement against Monte Carlo simulation at the percent level.

## Code

- [scintillator-pulse-analysis](https://github.com/ShanynHart/scintillator-pulse-analysis): feature extraction from digitised detector pulses. Time-series processing, sub-sample timing interpolation, pulse-shape discrimination, exponential model fitting.
- [gamma-calibration-pipeline](https://github.com/ShanynHart/gamma-calibration-pipeline): automated instrument calibration. Peak finding, constrained nonlinear regression, uncertainty propagation, batch pipelines.
- [coincidence-event-analysis](https://github.com/ShanynHart/coincidence-event-analysis): event building and classification across detector channels. Timestamped stream alignment, windowed joins, physics-constrained filtering, Cython-accelerated pandas.

Python (numpy, pandas, scipy, Cython), C++ (ROOT), and Monte Carlo simulation (TOPAS/Geant4).

## Research

First-author instrumentation paper on a LaBr3:Ce Compton camera (in preparation for Nuclear Instruments and Methods A): full statistical characterisation of a coincidence imaging system, including maximum-likelihood source localisation with coverage-tested confidence regions, Bayesian model selection, and detection-limit analysis.
