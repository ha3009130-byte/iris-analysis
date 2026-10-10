# Iris Dataset Analysis

## Project Overview

This project explores the Iris flower dataset using Python, Pandas, and Matplotlib. It focuses on data exploration, data quality checks, statistical analysis, filtering, visualization, and exporting results to CSV files.

## Objectives

- Explore the dataset structure and data types.
- Check for missing values and duplicate records.
- Calculate descriptive statistics for flower measurements.
- Compare measurements across the three Iris species.
- Filter records using measurement-based conditions.
- Visualize average petal length by species.
- Export analysis results for further use.

## Dataset

The dataset is stored in `data/iris.csv` and contains measurements for three Iris species:

- `setosa`
- `versicolor`
- `virginica`

The measurement columns are `sepal_length`, `sepal_width`, `petal_length`, and `petal_width`.

## Project Structure

```text
iris-analysis/
├── data/
│   └── iris.csv
├── output/
│   ├── species_summary.csv
│   └── filtered_iris.csv
├── iris_analysis.ipynb
├── pyproject.toml
├── uv.lock
├── .gitignore
└── README.md
```

## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- uv for project and dependency management

## Setup and Installation

### 1. Install the dependencies

Make sure Python and uv are installed. Open a terminal in the project directory and run:

```bash
uv sync
```

### 2. Start Jupyter Notebook

```bash
uv run jupyter notebook
```

Open `iris_analysis.ipynb` and run the cells from top to bottom.

## Analysis Workflow

1. Load the dataset into a Pandas DataFrame.
2. Inspect the first and last rows, dataset dimensions, and column types.
3. Check missing values and duplicate records.
4. Explore species counts and descriptive statistics.
5. Calculate average measurements by species.
6. Filter flowers based on measurement conditions.
7. Visualize average petal length across species.
8. Export the summary and filtered records to CSV files.

## Output Files

| File | Description |
|---|---|
| `output/species_summary.csv` | Summary of average measurements and sample counts by species |
| `output/filtered_iris.csv` | Records where `sepal_length > 6` |

## Key Findings

The analysis compares the measurements of the three Iris species. The average petal length is highest for `virginica` and lowest for `setosa`.

## Reproducibility

Run the notebook cells in order to reproduce the analysis and regenerate the output files. The project dependencies are managed through `pyproject.toml` and `uv.lock`.

## Author

Hisham Ahmed Jafri
