# ALFRED Reactor Core Model
A neutronics analysis project of the ALFRED reactor core using OpenMC and Python.

**Authors**: [Safius Sakib Shuddho](https://linkedin.com/in/sshuddho) and [Aqueeb Anjum Sunny](https://linkedin.com/in/aqueeb-sunny-509709313)  
[View Project](https://sshuddho.github.io/neutronics-alfred)

## Overview
This project presents an elementary neutronics analysis of the Advanced Lead-cooled Fast Reactor European Demonstrator (ALFRED), designed as a demonstrator for the European Lead-cooled Fast Reactor (ELFR), a GEN-IV nuclear reactor.

Utilizing [OpenMC](https://openmc.org), an open-source Monte Carlo neutron transport code, this project encompasses three key analyses:

1. Constructing the reactor core model with precise geometry and material definitions,
2. Calculating the neutron energy spectrum to understand the reactor’s neutron flux distribution across energy levels, and
3. Mapping the radial neutron flux distribution to visualize spatial variations within the core.
4. Mapping the power outputs from every fuel assembly to visualize the power distribution for the core.

Neutron flux values are normalized to ensure consistent and conventional units, facilitating accurate interpretation of the reactor’s behavior. Implemented in Python, the simulations leverage OpenMC’s capabilities alongside libraries like NumPy and Matplotlib for data analysis and visualization.  
This project, developed by Safius Sakib Shuddho and Aqueeb Anjum Sunny, showcases our expertise in nuclear reactor modeling and computational neutronics, demonstrating rigorous scientific methodology and advanced computational techniques.

## Notebooks
- [ALFRED Model](notebooks/ALFRED-model/ALFRED-model.ipynb)
- [Neutron Spectrum](notebooks/neutron-spectrum/neutron-spectrum.ipynb)
- [Radial Flux Distribution](notebooks/radial-flux/radial-flux.ipynb)
- [Power Distribution](notebooks/power-distribution/power-distribution.ipynb)

## Setup Instructions
To run the notebooks:
1.	Install OpenMC: See [OpenMC documentation](https://docs.openmc.org/en/stable/quickinstall.html).
2.	Download ENDF Data: See [Official Nuclear Data Libraries](https://openmc.org/official-data-libraries/)  
	Optionally Download [Depletion Chains](https://openmc.org/depletion-chains/) for Burnup Analysis
3.	Set `OPENMC_CROSS_SECTIONS` environment variable:
	```command
	export OPENMC_CROSS_SECTIONS='/path/to/data/library/cross_sections.xml'
4.	Install dependencies:
	```command
	pip install -r requirements.txt

