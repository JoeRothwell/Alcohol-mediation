# Metabolite mediators of alcohol intake for CRC

This repository contains the code for the metabolite mediators for alcohol intake and CRC project. Different metabolite mediators are prepared in the script `Make_alc_mediators.R`. The mediators are the first component of PLS models of the following:
* All Biocrates metabolites from CRC controls
* Amino acids from CRC controls
* Lipid metabolites from CRC controls
* All Biocrates metabolites from the controls of all EPIC studies
* Fatty acids from CRC controls
And also a few single metabolite mediators that were associated with alcohol intake in Eline's paper (to find ref)

Models and mediation analyses are then performed in `Alc_mediation_analysis.R`. 

Alc_mediation_function.R is the development of a function that runs models and automatically returns NDE, NIE and percentage mediated metrics. This is currently in development.
