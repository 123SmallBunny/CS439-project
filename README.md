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

Recommended notebook order:

1. `notebooks/clean_ACS.ipynb`
2. `notebooks/clean_FMR.ipynb`
3. `notebooks/clean_CPS.ipynb`
4. `Full_Merge/full_merge.ipynb`
5. `notebooks/eda.ipynb`
6. `notebooks/modeling.ipynb`
7. `notebooks/modeling2.ipynb`

The final EDA and modeling notebooks use the merged dataset in `Full_Merge/`.

## Requirements

Main Python packages used:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter
