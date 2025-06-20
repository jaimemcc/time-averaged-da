# time-averaged-da
This repository includes data and code used to generate a figure in the following paper:

Roitman MF & McCutcheon JE (2025). What’s the occasion? Phasic dopamine signaling and interoception. Current Opinion in Neurobiology.

The figure is based on data presented in full in the following paper:

Konanur et al. (2024). https://doi.org/10.1111/ejn.16214

## Data description
The data are taken from a fibre photometry experiment recording activity in dopamine neurons while rats ... Data in `snips_dict.pickle` have been preprocessed and aligned to onset of the infusion. For the paper, a representative rat was used - SVG135_FD - but data from other rats are also included in the .pickle file. The file `experiment_info_gsheet.xlsx` contains for metadata relating to the individual animals.

## Notebooks
The notebook `assemble_data.ipynb` was used to extract data from raw photometry data files. It cannot be run without these files.

The notebook `figure.ipynb` reads in the .pickle file and makes the figures used in the paper.

The notebook `animated_fig.ipynb` was used to make an animated GIF.