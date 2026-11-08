Heart Disease Analysis and Modeling

1. Project Introduction

This project uses the Heart Disease UCI dataset to perform classification, regression, and clustering. It also applies scenario analysis and sensitivity analysis to examine how changes in patient characteristics influence heart disease predictions.

2. Analytical Results Summary

The project applies classification, regression, and clustering techniques to analyze the dataset. Scenario analysis evaluated three situations: increased healthcare costs, an aging population, and increased air pollution.

The scenario analysis recorded the following changed predictions out of 184 test records:

- Increased Healthcare Costs: 6 changed predictions.
- Aging Population: 9 changed predictions.
- Increased Air Pollution: 8 changed predictions.

The sensitivity analysis examined patient age and maximum heart rate. Increasing age by five years and decreasing maximum heart rate by 5% each resulted in six changed predictions out of 184 test records. These findings indicate that changes in these patient characteristics can influence the model's classifications.

3. Dependencies

- Python
- pandas
- numpy
- scikit-learn
- TensorFlow
- matplotlib
- seaborn
- Jupyter Notebook

4. Running Instructions

4.1. Install Python and the required dependencies.
4.2. Place the `heart_disease_uci.csv` dataset in the project directory.
4.3. Open the project notebooks using Jupyter Notebook.
4.4. Run the notebook cells in order, starting with data preparation and model development.

