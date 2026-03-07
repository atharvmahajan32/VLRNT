# VLRNT: Valorant Data Analysis & Modeling

## Overview
VLRNT is a data science project focused on analyzing and modeling player performance in Valorant, a popular tactical shooter game. The project uses synthetic data to simulate and explore key metrics, visualize trends, and build predictive models for player evaluation and improvement.

## Project Structure

```
vlrnt/
│   pyproject.toml
│   README.md
│   uv.lock
├── data/
│   ├── valorant_scaled_data.csv
│   └── valorant_synthetic_data_raw.csv
├── notebooks/
│   ├── data-gen.ipynb
│   ├── eda.ipynb
│   ├── evaluation.ipynb
│   ├── prepsing-and-empmenting.ipynb
│   └── training.ipynb
├── visualizations/
│   ├── adr_boxplot.png
│   ├── cluster_evaluation_heatmap.png
│   ├── correlation_heatmap.png
│   ├── fb_vs_fd_scatter.png
│   └── key_metrics_pairplot.png
```

### Key Components
- **pyproject.toml**: Project configuration and dependencies.
- **uv.lock**: Dependency lock file.
- **data/**: Contains CSV files with scaled and raw synthetic Valorant data.
- **notebooks/**: Jupyter notebooks for data generation, exploratory data analysis (EDA), preprocessing, training, and evaluation.
- **visualizations/**: PNG files of key plots and heatmaps generated during analysis.

## Data Sources
- `valorant_scaled_data.csv`: Processed and scaled player data.
- `valorant_synthetic_data_raw.csv`: Raw synthetic data for experimentation and modeling.

## Notebooks
- **data-gen.ipynb**: Generates synthetic data for modeling and testing.
- **eda.ipynb**: Performs exploratory data analysis, including statistical summaries and visualizations.
- **evaluation.ipynb**: Evaluates model performance and clustering results.
- **prepsing-and-empmenting.ipynb**: Preprocessing and feature engineering steps.
- **training.ipynb**: Model training and validation.

## Visualizations
The `visualizations/` folder contains:
- **adr_boxplot.png**: Boxplot of Average Damage per Round (ADR).
- **cluster_evaluation_heatmap.png**: Heatmap for cluster evaluation.
- **correlation_heatmap.png**: Correlation matrix heatmap of features.
- **fb_vs_fd_scatter.png**: Scatter plot of First Blood vs First Death.
- **key_metrics_pairplot.png**: Pairplot of key player metrics.

## Usage

### Requirements
Install dependencies using [uv](https://github.com/astral-sh/uv) or your preferred Python package manager:

```powershell
uv sync
```

### Working with Notebooks
Open notebooks in Jupyter or VS Code to explore data, train models, and visualize results.

## Project Goals
- Analyze player performance metrics in Valorant.
- Generate and preprocess synthetic data for robust modeling.
- Build and evaluate predictive models for player ranking and clustering.
- Visualize key relationships and trends in player data.