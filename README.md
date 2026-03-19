## Project Overview
This project demonstrates a comprehensive data wrangling pipeline. Working with raw data from Inside Airbnb, it addresses the complexities of "dirty" data—handling missing values, identifying duplicates, and performing advanced string manipulations to extract features for price prediction.

## Key Learning Objectives
Data Imputation: Implementing logic-driven strategies to fill NaN values in critical columns.

Skewness & Transformation: Utilizing log transformations on the Price variable to normalize distributions for better model performance.

Feature Engineering: Processing complex strings (descriptions, amenities) into usable numerical or categorical data.

Performance Benchmarking: Validating the quality of the cleaning process by achieving a baseline RMSE of 0.3643 on log-transformed prices.

## Technical Stack
Python 3.x

Pandas & NumPy: Core data manipulation and transformation.

Scikit-Learn: Evaluation and preprocessing.

Matplotlib & Seaborn: Visualizing data distributions and missingness patterns.

## Repository Structure
Data Cleaning & Preparation using Airbnb Data_Student Template.ipynb: The primary Jupyter Notebook containing the step-by-step cleaning logic.

airbnb_photo.jpg: Documentation asset.

README.md: Project documentation.

## Methodology
Exploration: Identifying structural issues, duplicates, and the "sparsity" of the dataset.

Cleaning: Dropping redundant features and imputing missing data based on statistical measures (mean/median).

Preprocessing: Standardizing string formats and handling categorical encoding.

Evaluation: Training a preliminary model to ensure the cleaned features hold predictive power for property pricing.

## How to Use
Clone the repository:

Bash
git clone https://github.com/Oluwadara17/Data-Cleaning-and-Preparation-Airbnb-Dataset.git
Install requirements:

Bash
pip install pandas numpy scikit-learn matplotlib seaborn
Run the analysis:
Open the Jupyter Notebook and execute the cells to see the transformation pipeline in action.
