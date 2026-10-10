# FitTrack — Fitness Data Science Project

## Overview

FitTrack is a beginner data science project built with Python. It explores relationships among daily steps, sleep duration, exercise minutes, resting heart rate, water intake, and estimated calories burned using a year of synthetic fitness data.

The project demonstrates a complete introductory data science workflow, from dataset creation and cleaning to statistical analysis, visualization, and machine learning.

## Research Question

How are daily physical activity, sleep duration, exercise, and resting heart rate related within a simulated fitness dataset?

## Hypothesis

I hypothesized that activity and exercise measurements would show relationships with other simulated fitness measurements, including estimated calories burned and resting heart rate.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* GitHub

## Project Features

* Generated a dataset covering 365 simulated days
* Checked for missing values, duplicate records, and unexpected values
* Explored trends using charts and summary statistics
* Investigated correlations between variables
* Analyzed monthly and day-of-week patterns
* Built a linear regression model to predict estimated calories burned
* Evaluated the model using Mean Absolute Error (MAE) and R²
* Created a summary dashboard and documented project limitations

## Machine Learning

The project uses linear regression to predict the dataset's estimated calories burned from steps, sleep duration, resting heart rate, exercise minutes, and water intake.

Model performance is evaluated using MAE and R². The actual results are reported in the notebook and should be interpreted in the context of the synthetic data.

## Key Limitation

**The dataset is synthetic, not collected from real people.** Some relationships were intentionally built into the data-generation formula. The model therefore learns patterns that were partly designed by the project creator. Its results do not establish real-world health relationships and should not be used for medical or health decisions.

A future version could use a properly sourced real-world dataset and compare several modeling approaches.

## What I Learned

Through this project, I practiced creating and cleaning datasets, exploring data with visualizations, calculating correlations, training a machine learning model, evaluating predictions, and interpreting results responsibly. I also learned why understanding data limitations is essential before drawing conclusions.

## Repository Contents

* `FitTrack.ipynb` — Main notebook with code, analysis, charts, and results
* `fittrack_improved_data.csv` — Synthetic dataset used for the improved analysis
* `fittrack_correlation_results.csv` — Correlation summary
* `fittrack_predictions.csv` — Actual and predicted model results
* `fittrack_model_coefficients.csv` — Linear regression coefficients

Some CSV files may be absent if they have not been exported from the notebook.

## Reproducibility

The notebook was developed in Google Colab. Open it in Colab and run the cells in order to reproduce the analysis. The notebook uses a fixed random seed for its synthetic data generation.

## Project Status

Completed introductory data science portfolio project.
