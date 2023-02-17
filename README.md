# Porosity Prediction using Data Science Techniques
This project demonstrates how data science techniques can be used to predict porosity in subsurface geological formations. The data used in this project is synthetic, but the techniques demonstrated can be applied to real-world data.

## Getting Started
The following packages are required to run the code:

numpy
pandas
scipy
scikit-learn
matplotlib
seaborn
Data Generation
Synthetic data for porosity, depth, and lithology are generated using the beta distribution, uniform distribution, and random choice methods. The porosity values are then clipped to the range [0, 1] and noise is added to the data.

## Exploratory Data Analysis
Exploratory data analysis is conducted using scatter plots and box plots to understand the relationships between the features and the target variable.

## Data Preprocessing
The lithology data is label encoded and the depth and lithology features are combined into a single array for use in the model.

## Custom Support Vector Regression Model
A custom support vector regression model is built using scikit-learn. The model is trained on the training set and the mean absolute error is calculated on the testing set.

## Residual Analysis
Residual analysis is conducted by plotting the residuals against the predicted porosity values.

## Conclusion
This project demonstrates how data science techniques can be used to predict porosity in subsurface geological formations. The techniques demonstrated in this project can be applied to real-world data to improve our understanding of subsurface reservoirs.
