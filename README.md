# Iris Dataset Analysis Project

This project performs exploratory data analysis (EDA) and data manipulation on the classic Iris dataset using Python and Pandas, managed via `uv`.

## Project Structure
- `data/`: Contains the raw Iris dataset (`iris.csv`).
- `output/`: Contains processed CSV exports (`species_summary.csv`, `filtered_iris.csv`).
- `iris_analysis.ipynb`: The main Jupyter Notebook containing all analysis, filtering, summary statistics, and visualizations.
- `pyproject.toml` & `uv.lock`: Dependency and environment management files.

## Setup & Running Instructions
1. Ensure you have `uv` installed.
2. Clone or extract the project directory.
3. Synchronize dependencies and set up the environment:
   ```bash
   uv sync