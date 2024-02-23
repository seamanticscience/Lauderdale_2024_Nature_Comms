# Lauderdale_2024_NCOMMS2334222A
<!-- [![DOI](https://zenodo.org/badge/207910435.svg)](https://zenodo.org/badge/latestdoi/207910435) -->
![GitHub release (latest by date)](https://img.shields.io/github/v/release/seamanticscience/Lauderdale_2024_NCOMMS2334222A?color=1b3370)
![GitHub last commit](https://img.shields.io/github/last-commit/seamanticscience/Lauderdale_2024_NCOMMS2334222A?color=f44323)
![GitHub License](https://img.shields.io/github/license/seamanticscience/Lauderdale_2024_NCOMMS2334222A?color=ffa500)
<!-- <a href="https://doi.org/10.1073/pnas.1917277117"><img src="http://img.shields.io/badge/paper%20link-doi:10.1073%2Fpnas.1917277117-lightgrey.svg" alt="Link to paper at https://doi.org/10.1073/pnas.1917277117"></a> -->

Box model code, processing routines, and model ensemble data for the paper "Ocean iron cycle feedbacks decouple atmospheric CO<sub>2</sub> from meridional overturning circulation changes" by Jonathan Maitland Lauderdale. <!-- in Proceedings of the National Academy of Sciences. -->

Everything is controlled via the two Jupyter Notebooks:

`1_spinup_microCOSM_6box.ipynb` creates the fixed and variable ligand control runs, and

`2_run_microCOSM_psi_ensemble_6box.ipynb` performs the MOC ensemble runs, and sensitivity tests.

Packages required include `Matplotlib`, `Numpy`, `Pandas`, `Scipy`, and optionally `Pandarallel` for parallel runs.

Any questions or comments, please get in contact!
