# ALFRED Reactor Core Model
A portfolio showcasing neutronics analysis of the ALFRED reactor using OpenMC and Python.

**Authors**: Safius Sakib Shuddho and Aqueeb Anjum Sunny

[View Portfolio](https://SShuddho.github.io/neutronics-alfred)

Below is your updated **Overview** section formatted as Markdown for the `README.md` file, with the key analyses presented as a numbered list to match your provided text. The content remains unchanged, ensuring the mention of flux normalization and all other details are preserved.

## Overview
This project presents an elementary neutronics analysis of the Advanced Lead-cooled Fast Reactor European Demonstrator (ALFRED), designed as a demonstrator for the European Lead-cooled Fast Reactor (ELFR), a GEN-IV nuclear reactor.

Utilizing [OpenMC](https://openmc.org), an open-source Monte Carlo neutron transport code, this project encompasses three key analyses:

1. Constructing the reactor core model with precise geometry and material definitions,
2. Calculating the neutron energy spectrum to understand the reactor’s neutron flux distribution across energy levels, and
3. Mapping the radial neutron flux distribution to visualize spatial variations within the core.

Neutron flux values are normalized to ensure consistent and conventional units, facilitating accurate interpretation of the reactor’s behavior. Implemented in Python, the simulations leverage OpenMC’s capabilities alongside libraries like NumPy and Matplotlib for data analysis and visualization. This portfolio, developed by Safius Sakib Shuddho and Aqueeb Anjum Sunny, showcases our expertise in nuclear reactor modeling and computational neutronics, demonstrating rigorous scientific methodology and advanced computational techniques.

### **Steps to Update**
1. **Edit `README.md`**:
   - Open `README.md` in your `neutronics-alfred/` directory.
   - Replace the existing **Overview** section with the Markdown content above (from `## Overview` to the end of the section).
   - Ensure the rest of `README.md` (e.g., Authors, Notebooks, Source Code, Setup Instructions) remains intact.

2. **Stage and Commit**:
   ```bash
   git add README.md
   git commit -m "Updated README Overview with numbered list format"
   git push origin main
   ```

3. **Verify**:
   - Visit `https://github.com/SShuddho/neutronics-alfred` to confirm the **Overview** section renders correctly with the numbered list.
   - Ensure the OpenMC link (`https://openmc.org`) and other sections display as expected.

---

### **Notes**
- The numbered list format mirrors your provided text, using Markdown’s `1.`, `2.`, `3.` syntax for clarity.
- The artifact is provided as a partial `README.md` section, as you only requested the **Overview** part. If you need the full `README.md`, let me know, and I can integrate it.
- If you want further tweaks (e.g., different wording or additional details), share them, and I’ll adjust the text.

Let me know if you need help with the update or further refinements!

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
