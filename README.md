# Organoboron-OLED-Multiscale

This repository contains the computational input files, processed data, and OLED simulation parameters associated with the manuscript:

**“Charge transport, excited-state dynamics, and OLED performance of four-coordinate organoboron emitters: a multiscale computational study.”**

The repository is provided to support transparency, reproducibility, and access to the computational data used in the study.

## Repository Contents

### `Input files/`

Gaussian input files (`.gjf`) used for quantum-chemical calculations of the investigated organoboron compounds.

These files contain the molecular structures and computational settings used for the DFT calculations.

### `equation files/`

Processed numerical data and analysis files used in the manuscript, including:

- Marcus-theory related calculations
- Quantum chemical descriptors (QCDs)
- Reorganization energies
- TADF-related photophysical parameters
- Other derived computational quantities used in the analysis

### `2band2e_bumblebee/`

Input and property files used for the OLED device simulations of compounds **2b** and **2e** with Bumblebee.

The folder contains:

- `2b_params.yml`
- `2b_properties.yml`
- `2e_params.yml`
- `2e_properties.yml`

These YAML files contain the molecular and photophysical parameters required for the device-level simulations.

## Computational Workflow

The computational workflow combines molecular-level quantum-chemical calculations with charge-transport, excited-state, and OLED device simulations.

The main stages include:

1. Molecular geometry and electronic-structure calculations
2. Calculation of charge-transport parameters
3. Evaluation of excited-state and TADF-related properties
4. Determination of reorganization energies and related descriptors
5. OLED device simulations using Bumblebee

## Software

The calculations and simulations reported in the manuscript were performed using computational chemistry and OLED simulation software, including:

- Gaussian
- AMS/ADF
- Bumblebee

The corresponding input and processed data files are provided in the relevant directories.

## Data Availability

The files provided in this repository contain the computational inputs and numerical data required to reproduce the main computational analyses presented in the manuscript.

Additional methodological details, computational settings, and interpretation of the results are provided in the associated manuscript and Supporting Information.

## Citation

If you use the data or computational workflow provided in this repository, please cite the associated publication.

Publication details and DOI will be added after publication.

## Authors

**Bekir Kahriman**  
**Ayhan Üngördü**

Department of Chemistry, Faculty of Science,  
Sivas Cumhuriyet University, Sivas, Türkiye

## Corresponding Author

**Ayhan Üngördü**  
E-mail: aungordu@cumhuriyet.edu.tr
