# Copilot Instructions for Data Science Workspace

## Overview
This workspace is a collection of Jupyter notebooks focused on foundational and intermediate data science concepts, including statistics, probability, hypothesis testing, and machine learning. Each notebook is self-contained and covers a specific topic, with code, explanations, and visualizations.

## Project Structure
- All work is organized as Jupyter notebooks in the root directory.
- There are no Python scripts, modules, or package structures—each `.ipynb` file is standalone.
- Notebooks include:
  - `Central_Limit_Theorem.ipynb`
  - `Hypothesis_Testing.ipynb`
  - `Machine_Learning.ipynb`
  - `Measure_Of_variability.ipynb`
  - `MeasuresOfShape.ipynb`
  - `Probability.ipynb`
  - `covariance_and_correlation.ipynb`
  - `percentage&percentail&quartiles.ipynb`
  - `statistics.ipynb`

## Key Patterns and Conventions
- Use Python (typically with pandas, numpy, matplotlib, seaborn, and scikit-learn) for all code cells.
- Each notebook is structured with explanations in markdown cells and code in code cells.
- Visualizations are generated inline using matplotlib or seaborn.
- Data is either generated within the notebook or loaded from standard datasets (no external data files in the repo).
- Naming: Notebook filenames use underscores for spaces and are descriptive of their content.

## Developer Workflows
- No build or test system is present; all work is interactive via Jupyter.
- To run or modify code, open the relevant notebook in Jupyter and execute cells as needed.
- If a new topic is added, create a new notebook following the existing naming and structure conventions.
- For package management, install required Python packages in the notebook using `!pip install package-name` if not already available.

## Integration and Dependencies
- No cross-notebook imports or shared modules—each notebook is independent.
- Standard Python data science libraries are used; no custom or external dependencies beyond pip-installable packages.

## Example: Adding a New Notebook
1. Name the file descriptively, e.g., `Regression_Analysis.ipynb`.
2. Start with a markdown cell explaining the topic.
3. Add code cells for data generation, analysis, and visualization.
4. Use inline comments and markdown for clarity.

## Key Files
- All `.ipynb` files in the root directory are primary sources of knowledge and examples.
- No README or meta-documentation is present; use notebook content for guidance.

---

For questions about conventions or structure, review existing notebooks for examples.
