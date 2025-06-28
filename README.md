# ALFRED Reactor Core Model
A portfolio showcasing neutronics analysis of the ALFRED reactor using OpenMC and Python.

**Authors**: Safius Sakib Shuddho and Aqueeb Anjum Sunny

[View Portfolio](https://SShuddho.github.io/neutronics-alfred)

## Overview
This project models the ALFRED reactor core, calculates its neutron energy spectrum, and maps its radial flux distribution using OpenMC.

## Notebooks
- [ALFRED Model](notebooks/ALFRED-model/ALFRED-model.ipynb)
- [Neutron Spectrum](notebooks/neutron-spectrum/neutron-spectrum.ipynb)
- [Radial Flux](notebooks/radial-flux/radial-flux.ipynb)

## Source Code
- [ALFRED Model](src/ALFRED-model.py)
- [Neutron Spectrum](src/neutron-spectrum.py)
- [Radial Flux](src/radial-flux.py)

## Setup Instructions
To run the notebooks or scripts:
1. Install OpenMC: See [OpenMC documentation](https://docs.openmc.org/en/stable/quickinstall.html).
2. Download ENDF Data: See [Official Nuclear Data Libraries](https://openmc.org/official-data-libraries/)
3. Set `OPENMC_CROSS_SECTIONS` environment variable.
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
