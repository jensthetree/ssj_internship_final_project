# BRI Public Report
This repository contains all the raw code of my work for BRI studying bird species distribution shifts in Maine.
No raw data  are included in this repository as they are the property of BRI.
Although they cannot be run without the raw data, the ```.Rmd``` files run on R version ```4.4.1``` and follow this pipeline:
1. ```data-manipulation.Rmd``` cleans the raw data.
2. ```bias_adj.Rmd``` adds adjustment values based on the geographic bias of the data.
3. ```analysis.Rmd``` performs statistical analysis and plots the results.

The pdf bird_species_shift_basic_summary is a one-page description of my work at BRI.
Data analysis and research for a paper that I plan to publish with Evan Adams on the geographic shifts among bird species in Maine is ongoing. Expected publication: 2026.
