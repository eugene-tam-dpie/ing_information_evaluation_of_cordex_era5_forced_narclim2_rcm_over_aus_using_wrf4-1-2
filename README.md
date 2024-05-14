# NARCLiM2.0 Design and Evaluation manuscript supporting information #

## Executive Summary ##

This repository contains supporting information for the manuscript titled "Evaluation of CORDEX ERA5-forced ‘NARCliM2.0’ regional climate models over Australia using the Weather Research and Forecasting (WRF) model version 4.1.2
", by Giovanni Di Virgilio, Fei Ji, Eugene Tam, Jason Evans, Jatin Kala, Julia Andrys, Christopher Thomas, Dipayan Choudhury, Carlos Rocha, Yue Li, and Matthew Riley, submitted to Geoscientific Model Development on 2024-04-15.

The manuscript is available with the DOI [10.5194/gmd-2024-41-CEC1](https://dx.doi.org/10.5194/gmd-2024-41-CEC1)

We ask everyone who uses or adapts our scripts to acknowledge the NSW Department of Climate Change, Energy, Environment and Water 2024 (NSW DCCEEW), not to be mistaken with our Federal counterpart.

Additional information can be found on the [NSW Climate Data Portal](https://climatedata-beta.environment.nsw.gov.au/)

## Repository Structure ##

The included supported materials include

* **WRF code and configuration**
  * **Snapshots of the version of WRF/WPS source code** (within the `WRF/source_code` subdirectory) used
  * **Namelists (configuration files)** used to generate boundary/initial conditions from metgrid outputs as well as downscale ERA5 using the boundary/initial condition files generated within the `WRF/input_files` subdirectory.
* **ERA5 pre-processing scripts and configuration** including
  * **era5grib**, a python script that directly processed the ERA5 outputs and generates metgrid files within the `era5grib/source_code` subdirectory
  * **Namelists (configuration files)** used used as inputs for era5grib `era5grib/input_files`

## Acknowledgements ##

We acknowledge

* Climate Change Fund
* Other funding bodies

## References ##

1. Di Virgilio Giovanni, F. Ji, E. Tam, N. Nishant, J. P. Evans, C. Thomas, M. Riley, K. Beyer, M. Grose, S Narsey, F Delage. (2022). Selecting CMIP6 GCMs for CORDEX dynamical downscaling: model performance, independence, and climate change signals, Earth's Future, DOI: [10.1029/2021EF002625](https://dx.doi.org/10.1029/2021EF002625)

2. Di Virgilio Giovanni, F. Ji, E. Tam, J. P. Evans, J. Kala, J. Andrys C. Thomas, D. Choudhury, C. Rocha, Y. Li, M. Riley (Under review) Evaluation of CORDEX ERA5-forced ‘NARCliM2.0’ regional climate models over Australia using the Weather Research and Forecasting (WRF) model version 4.1.2, Geoscientific Model Development, DOI: [10.5194/gmd-2024-41](https://dx.doi.org/10.5194/gmd-2024-41)

3. Di Virgilio Giovanni, J. P. Evans, F. Ji, E. Tam, J. Kala, J. Andrys, C. Thomas, D. Choudhury, C. Rocha, S. White, Y. Li, M. El Rafei, R. Goyal and M. Riley (Under review) Design, evaluation and future projections of the NARCliM2.0 CORDEX-CMIP6 Australasia regional climate ensemble, Geoscientific Model Development
