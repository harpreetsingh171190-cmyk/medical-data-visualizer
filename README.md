# Medical Data Visualizer

This project is part of the **Data Analysis with Python** certification from freeCodeCamp. It uses Python, Pandas, Seaborn, and Matplotlib to visualize and make calculations from medical examination data.

## Features & Analysis Performed
- **Overweight Column:** Calculates BMI to add an overweight column (BMI > 25 is 1, else 0).
- **Data Normalization:** Normalizes cholesterol and glucose values (0 for good, 1 for bad).
- **Categorical Plot (`draw_cat_plot`):** Creates a categorical split chart showing counts of good and bad outcomes for features like cholesterol, glucose, alcohol, active, and smoke for patients with `cardio = 1` and `cardio = 0`.
- **Heat Map (`draw_heat_map`):** Cleans incorrect patient segment data (blood pressure and height/weight percentiles) and plots a correlation matrix heatmap using Seaborn.

## Technologies Used
- Python
- Pandas
- Seaborn
- Matplotlib
- Google Colab / Jupyter Notebooks

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run the cells to process the data and generate the charts.
