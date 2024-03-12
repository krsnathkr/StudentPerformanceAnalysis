# Student Performance Analysis and Predictor

## Introduction
This project analyzes factors influencing student performance and predicts final grades using a linear regression model.

## Description
The "Student Performance Analysis and Predictor" project aims to explore the factors influencing student academic performance and develop a predictive model for final grades. By analyzing a dataset containing various attributes such as hours studied, extracurricular activities, sleep hours, and previous scores, this project seeks to uncover patterns and correlations that can provide valuable insights into student success.

Through exploratory data analysis (EDA), the project investigates the relationships between different variables and the performance index, leveraging visualizations like pair plots and correlation heatmaps. This phase helps identify key predictors of performance and informs feature selection for the predictive model.

Subsequently, a linear regression model is employed to predict the performance index based on the selected features. The model is trained on a portion of the dataset and evaluated for accuracy using metrics like the coefficient of determination (R^2) and root mean squared error (RMSE). Additionally, a scatter plot is generated to visualize the predicted performance index against the true values, allowing for a qualitative assessment of the model's efficacy.

By providing a comprehensive analysis of student performance factors and offering a predictive tool, this project serves as a valuable resource for educators, administrators, and policymakers seeking to understand and support student success in academic settings.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage
1. Clone/download repository.
2. Ensure `Student_Performance.csv` is in the same directory.
3. Run `Student_Performance_Analysis_Predictor.ipynb`.
4. Follow notebook instructions.

## Features
### Exploratory Data Analysis (EDA)
- Utilizes visualizations such as pair plots and correlation heatmaps to explore relationships between variables like hours studied, extracurricular activities, sleep hours, previous scores, and the performance index.
- Provides insights into which variables have the strongest correlation with the performance index, aiding in feature selection for modeling.

### Linear Regression Model
- Implements a linear regression model to predict the performance index based on features identified during EDA.
- Splits the dataset into training and testing sets, performs standardization on the features, and trains the model using the training data.
- Evaluates model performance using metrics such as the coefficient of determination (R^2) and root mean squared error (RMSE).
- Generates a scatter plot to visualize the predicted performance index against the true values, accompanied by model statistics for assessment.

## Files
- `Student_Performance.csv`: Dataset containing student performance and related attributes.
    - https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression/data 
- `Student_Performance_Analysis_Predictor.ipynb`: Jupyter Notebook containing code for data analysis and model building.
- `README.md`: Overview of the project, installation instructions, usage guidelines, and feature details.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
