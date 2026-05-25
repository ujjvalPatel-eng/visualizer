# iPhone Sales Visualizer

This repository contains a Jupyter notebook for exploring and visualizing an iPhone sales dataset.

## Contents

- `Visulizer.ipynb`: Main notebook with interactive sales data exploration, data cleaning, dataframe operations, and visualization tools.
- `iphone_sales_dataset.csv`: Sample sales dataset used by the notebook.

## Features

- Load sales data from a CSV file
- Display dataset summary and preview rows
- Explore columns, basic info, and descriptive statistics
- Handle missing values
- Perform common dataframe operations (filter, sort, group, max/min, add column)
- Create plots using seaborn and matplotlib
- Exit menus cleanly with `Enter`, `q`, `quit`, `esc`, or menu option `6`
- Saved plots are stored in the `saved_plots/` folder

## Requirements

- Python 3.8 or newer
- pandas
- seaborn
- matplotlib

## Installation

Install the required Python packages using pip:

```bash
pip install pandas seaborn matplotlib
```

## Usage

1. Open `Visulizer.ipynb` in Jupyter Notebook or JupyterLab.
2. Run the notebook cells.
3. In the first interactive menu, load the dataset by entering the CSV file path such as:

```text
iphone_sales_dataset.csv
```

4. Use the menu options to explore, clean, analyze, and visualize the data.

## Notes

- The notebook uses text input prompts for navigation.
- To quit interactive menus quickly, press `Enter` on an empty prompt or type `q`, `quit`, or `esc`.
