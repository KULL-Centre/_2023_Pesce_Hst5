### Data and scripts for Pesce and Lindorff-Larsen 2023

## Requirements used:
- BME reweighting requires https://github.com/KULL-Centre/BME

- Block analysis requires https://github.com/fpesceKU/BLOCKING

- Simulations and PBMetaD data are available at https://doi.org/10.17894/UCPH.4D0D9A09-B40B-4A3A-93EF-D6C249F49A90

## List of content:
- **HST5_MD_analysis.ipynb**: notebook used to analyze simulations and produce the figures for the paper.
- **CV/**: folder containing collective variables and PBMetaD bias calculated from simulations.
- **PLUMED/**: plumed input files used to activate PBMetaD and calculate the bias.
- **SAXS_exp/***: experimental SAXS profiles with errors corrected via the BIFT approach.
- **iBME/***: results and stats from reweighting simulations against SAXS.

*Run unpack.sh to decompress folder content!
