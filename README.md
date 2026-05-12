# CS439 Housing Project

Nicholas Martino, Catherine Zhou, Keith Denila

CS439 final project on housing affordability and homeownership in New Jersey from 2005 to 2023.

## Folders

- `data/` raw source data
- `clean_data/` cleaned intermediate data
- `Full_Merge/` merged project data
- `Figures/` final charts and plots
- `notebooks/` cleaning, EDA, and modeling notebooks

## Main File

The main final dataset is:

```text
Full_Merge/MERGED_GENERATIONS.csv
```

## How to Run

Open the project folder in Jupyter Notebook or JupyterLab.

For the final results, run:

1. `notebooks/eda.ipynb`
2. `notebooks/modeling.ipynb`
3. `notebooks/modeling2.ipynb`

The final EDA and modeling notebooks use the merged dataset in `Full_Merge/`.

The cleaning and merge notebooks are included to show the data preparation process:

- `notebooks/clean_ACS.ipynb`
- `notebooks/clean_FMR.ipynb`
- `notebooks/clean_CPS.ipynb`
- `Full_Merge/full_merge.ipynb`

The CPS raw files are large and the fixed-width column positions can change by year, so the cleaned CPS file used for the final project is already included in `Full_Merge/`.

## Requirements

Main Python packages used:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

## Raw CPS Data

The large CPS ASEC raw files are not stored directly in this GitHub repository because some files are over GitHub's normal file size limit.

They are attached separately in the GitHub Release for this project as `ASEC_RAW.zip`.

To rerun CPS cleaning, download `ASEC_RAW.zip`, unzip it into the project root, and make sure the folder path is:

```text
ASEC_RAW/
```
