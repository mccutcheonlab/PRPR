# PRPR

This repository contains analysis code for experiments studying motivation in protein-restricted rats using progressive ratio responding for food pellets. These findings will be published in Chiacchierini et al. (2022) *bioRxiv*. Full citation to follow.

The main notebook (*PRPR analysis.ipynb*) contains code that will download data from a repository and extract parameters into pandas dataframes. Figures from the paper are also recreated using *matplotlib*.

An *environment.yml* file is included that can be used to install necessary modules/packages. To do this, use Anaconda/Miniconda to create an environment by navigating to the folder and using the following command:

    conda env create -f environment.yml

The raw datafiles are Med Associates files in the stripped format. Timestamps of individual lever presses and reward deliveries are included in the raw datafiles and can be extracted but are not used here. Datafiles are included as a .zip file hosted on Zenodo along with metafiles which contain information on rat, day, session type etc.
