# Motility-induced phase separation drives aggregation in chemotactic systems

This repository contains Jupyter notebooks for the analysis and simulations of a unified continuum framework combining chemotaxis and motility-induced phase separation (MIPS), with minimal and autocrine signalling.
![Uploading AdobeExpressPhotos_931351a6cd5a49fca084c93c79f38d98_CopyEdited.png…]()


### Code organisation

- `figure_2_phase_diagram.ipynb` - Generates the phase diagram in Fig. 2.
- `figure_3_dispersion_relation.ipynb` - Calculates and plots the dispersion relations in Fig. 3.
- `figure_4_Autocrine_CMIPS_Simulation.ipynb` - Simulates pattern formation in the autocrine CMIPS model for Fig. 4.
- `figure_5_Minimal_CMIPS_Simulation.ipynb` - Simulates pattern formation in the minimal-signaling CMIPS model for Fig. 5.
- `figure_6_pattern_transmission.ipynb` - Simulates pattern transmission between a MIPS-unstable population and a stable population, comparing minimal and autocrine signaling for Fig. 6.
- `Supplementary_figure1_autocrine_KS.ipynb` - Calculates and plots the dispersion relation for the autocrine Keller–Segel model in Supplementary Fig. S1.
- `Supplementary_coarsening_analysis.ipynb` - Analyses coarsening in the minimal-signaling and autocrine CMIPS models, including characteristic domain size and power-law fits.
- `Supplementary_two_population_simulation.ipynb` - Provides supplementary two-population simulations and analysis of spatial Pearson correlation and enrichment within MIPS-defined aggregates.

For details on model parameters and implementation, see the comments in each notebook.

***

### Requirements

To run the notebooks, you need:

- Python 3
- NumPy
- Matplotlib
- Jupyter Notebook or JupyterLab

Run the cells in each notebook in order. Where plotting cells load saved data, update the file paths to match your local setup. Simulation runtime depends on the grid size, number of time steps, and hardware.

***

### Contacts

Prof. Robert Endres: r.endres@imperial.ac.uk
