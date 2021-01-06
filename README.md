# The Distribution of Cellular Turnover in the Human Body

This repository contains all source data and code for the analysis found in ["The Distribution of Cellular Turnover in the Human Body"](https://www.nature.com/articles/s41591-020-01182-9) by Ron Sender and and Ron Milo (Nature Medicine, 2021). 

Most of the files are given per tissue:

    1. The source data is provided in .xlsx file

    2. The source code is given in a .ipynb file

In addition two general notebooks: one contains utility functions and the other a code for running all the notebooks at ones.  
The results are saved in another .xlsx file, a spreadsheet for each tissue.

---

An index for the structure of this repository is given below:

### Utility and summary: 

* **[`Utility_Functions.ipynb`](Utility_Functions.ipynb)|** code for defining utility functions for the calculations. For example the definition of a class that contains database of the properties of cell types of a given tissue.

* **[`Results_summary.ipynb`](Results_summary.ipynb)|** code for running the entire analysis, by calling the various notebooks.

* **[`Summary.xlsx`](Summary.xlsx)|** in this excel file, the results are being saved. Each cell type in its unique spreadsheet.

### Tissue's data and analysis:

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

* **[`Lung_cells.ipynb`](Lung_cells.ipynb)|** code for estimating the number and turnover rates of lung cells

* **[`Lung_cells_data.xlsx`](Lung_cells_data.xlsx)|** curated data from the literature for estimating the number and turnover rates of lung cells

* **[`Lymphocytes.ipynb`](Lymphocytes.ipynb)|** code for estimating the number and turnover rates of the lymphoctes

* **[`Lymphocytes_data.xlsx`](Lymphocytes_data.xlsx)|** curated data from the literature for estimating the number and turnover of the lymphoctes 

* **[`Monocytes.ipynb`](Monocytes.ipynb)|** code for estimating the number and turnover rates of the monocytes

* **[`Monocytes_data.xlsx`](Monocytes_data.xlsx)|** curated data from the literature for estimating the number and turnover of the monocytes

* **[`Myocytes.ipynb`](Myocytes.ipynb)|** code for estimating the number and turnover rates of the muscle cells

* **[`Myocytes_data.xlsx`](Myocytes_data.xlsx)|** curated data from the literature for estimating the number and turnover of the muscle cells

* **[`Neutrophils.ipynb`](Neutrophils.ipynb)|** code for estimating the number and turnover rates of the neutrophils

* **[`Neutrophils_data.xlsx`](Neutrophils_data.xlsx)|** curated data from the literature for estimating the number and turnover of the neutrophils

* **[`Skin_cells.ipynb`](Skin_cells.ipynb)|** code for estimating the number and turnover rates of the skin cells (epidermal and deraml cells)

* **[`Skin_cells_data.xlsx`](Skin_cells_data.xlsx)|** curated data from the literature for estimating the number and turnover of the skin cells (epidermal and deraml cells)

