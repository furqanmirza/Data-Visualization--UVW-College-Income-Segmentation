# Curated Income Analysis - Data Visualization

This repository contains a Jupyter Notebook (`Data-Visualization--UVW-College-Income-Segmentation.ipynb`) that performs data visualization and segmentation analysis on an income dataset. The goal of this project is to explore demographic and employment factors that influence whether an individual earns more or less than $50K annually.

## Dataset
The dataset used in this analysis contains demographic and employment information, such as:
- Age
- Workclass
- Education and Education Number
- Marital Status
- Occupation
- Relationship
- Race
- Sex
- Capital Gain and Loss
- Hours Worked per Week
- Income (`<=50K` or `>50K`)

This dataset is characteristic of the well-known "Adult Census Income" dataset.

## Visualizations

The notebook features a curated set of exactly five impactful visualizations to uncover insights from the data:

1. **Age Distribution by Income**: Examines how age correlates with income levels.
2. **Education Level vs Income**: A bar chart demonstrating the impact of educational attainment on the likelihood of earning >$50K.
3. **Pay Disparity (> $50K Rate) by Race × Gender**: A heatmap visualizing the intersectional pay disparities across different racial and gender groups.
4. **Hours Worked vs Age by Income**: A scatter plot exploring the relationship between age, weekly hours worked, and income outcomes.
5. **Marital Status × Income**: A mosaic plot (or similar proportional chart) highlighting the proportion of high vs. low earners across various marital statuses.

## Technologies Used
- **Python**
- **Pandas**: For data manipulation, cleaning, and preprocessing.
- **Matplotlib & Seaborn**: For creating the visualizations and charts.

## How to Run

1. Clone the repository.
2. Ensure you have Python installed, along with Jupyter Notebook or JupyterLab.
3. Install the required libraries: pandas, matplotlib, seaborn
