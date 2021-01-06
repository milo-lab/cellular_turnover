# The Distribution of Cellular Turnover in the Human Body

This repository contains all source data and code for the analysis found in ["The Distribution of Cellular Turnover in the Human Body"](https://www.nature.com/articles/s41591-020-01182-9) by Ron Sender and and Ron Milo (Nature Medicine, 2021). 

Most of the files are given per tissue:

    1. The source data is provided in .xlsx file

    2. The source code is given in a .ipynb file

In addition two general notebooks: one contains utility functions and the other a code for running all the notebooks at ones.  
The results are saved in another .xlsx file, a spreadsheet for each tissue.

An index for the structure of this repository is given below:

* **[`Adipocytes.ipynb`](./Adipocytes.ipynb)|** code for estimating the number and turnover rates of adipocytes (fat cells)

* **[`Adipocytes_data.xlsx`](./Adipocytes_data.xlsx)|** curated data from the literature for estimating the number and turnover rates of adipocytes (fat cells)

* **[`Brain_cells.ipynb`](./Brain_cells.ipynb)|** code for estimating the number and turnover rates of brain cells: neurons and glial cells

* **[`Brain_data.xlsx`](/Brain_data.xlsx)|** curated data from the literature for estimating the number and turnover rates of brain cells: neurons and glial cells

* **[`Cardiomyocytes.ipynb`](Cardiomyocytes.ipynb)|** code for estimating the number and turnover rates of heart cells, mainly cardiomyocytes

* **[`Cardiomyocytes_data.xlsx`](Cardiomyocytes_data.xlsx)|** curated data from the literature for estimating the number and turnover rates of heart cells, mainly cardiomyocytes

* **[`Endothelial_cells.ipynb`](Endothelial_cells.ipynb)|** code for estimating the number and turnover rates of endothelial cells

* **[`Endothelial_cells_data.xlsx`](Endothelial_cells_data.xlsx)|** curated data from the literature for estimating the number and turnover rates of endothelial cells

* **[`Erythrocytes.ipynb`](Erythrocytes.ipynb)|** code for estimating the number and turnover rates of erythrocytes (RBC)

* **[`RBC_data.xlsx`](RBC_data.xlsx)|** curated data from the literature for estimating the number and turnover rates of erythrocytes (RBC)

* **[`GIT_Epithelial_cells.ipynb`](GIT_Epithelial_cells.ipynb)|** code for estimating the number and turnover rates of the epithelial cells of the GI tract (stomach, small and large intestine)

* **[`GIT_epithel_data.xlsx`](GIT_epithel_data.xlsx)|** curated data from the literature for estimating the number and turnover rates of the epithelial cells of the GI tract (stomach, small and large intestine)

* **[`Liver_cells.ipynb`](Liver_cells.ipynb)|** code for estimating the number and turnover rates of liver cells

* **[`Liver_cells_data.xlsx`](Liver_cells_data.xlsx)|** curated data from the literature for estimating the number and turnover rates of liver cells





* **[`bacteria_archaea/`](./bacteria_archaea)|** Data and code for estimating the total biomass of bacteria & arechaea

* **[`fungi/`](./fungi)|** Data and code for estimating the total biomass of fungi

* **[`protists/`](./protists)|** Data and code for estimating the total biomass of fungi

* **[`animals/`](./animals)|** Data and code for estimating the total biomass of animals

* **[`viruses/`](./viruses)|** Data and code for estimating the total biomass of viruses

* **[`MAREDAT_consistency_check/`](./MAREDAT_consistency_check)|** Consistency checks for estimates based on the MARine Ecosystem DATa (MEREDAT)

* **[`figures/`](./figures)|** Code for generating the figures in the manuscript and scripts for calculating the probability of plants dominating biomass and for calculating the probability the marine trophic pyramid is inverted

* **[`statistics_helper/`](./statistics_helper)|** Helper functions for generating our best estimates as well as uncertainty projections

* `summary.xlsx`| An excel file summarizing the results of the study

* `run_pipeline.py`| A script for running the entire analysis and regenerating the results

* `global_biomass.ipynb`| A Jupyter notebook estimating the total biomass on Earth

Each directory contain Jupyter notebooks detailing the analysis leading to our estimates. To make our analysis accessible, we provide the notebooks in three file formats: `.ipynb` files, `.html` files and `.py` files.

