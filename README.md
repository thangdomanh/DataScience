# Data Science Notebook Examples

This repository contains a small collection of Jupyter notebooks for practicing
data analysis with Python and pandas. The notebooks work through classic example
datasets and demonstrate common exploratory data analysis tasks such as loading
raw data, cleaning and reshaping tables, aggregating records, and visualizing
trends.

## Contents

- `ch2_1_usa.gov_data_from_bitly.ipynb` explores usa.gov URL shortening data
  from Bitly. It counts time zones first with pure Python and then with pandas.
- `ch2_2_MovieLens-1M-Data-Set.ipynb` analyzes the MovieLens 1M ratings data by
  combining users, ratings, and movie metadata, then comparing rating patterns.
- `ch2_3_US_Baby_Names_1880-2010.ipynb` analyzes U.S. baby name records from
  1880 through 2010, including naming trends, diversity, last-letter patterns,
  and names that shifted between genders.
- `Notebook&Datasets.zip` appears to contain the supporting notebooks and data
  files used by the examples.

## Requirements

The notebooks are intended to run in a Python environment with:

- Jupyter Notebook or JupyterLab
- pandas
- numpy
- matplotlib

Install the main dependencies with:

```bash
pip install jupyter pandas numpy matplotlib
```

## Getting Started

1. Extract `Notebook&Datasets.zip` if the dataset folders are not already present
   in the project directory.
2. Start Jupyter from this directory:

   ```bash
   jupyter notebook
   ```

3. Open one of the `ch2_*.ipynb` notebooks and run the cells in order.

## Dataset Folders

The notebooks expect these data folders to exist next to the notebooks after the
zip file is extracted:

- `bitly_usagov/`
- `ml-1m/`
- `names/`

If a notebook cannot find a file, confirm that the zip archive has been
extracted and that the resulting dataset folders are in the repository root.
