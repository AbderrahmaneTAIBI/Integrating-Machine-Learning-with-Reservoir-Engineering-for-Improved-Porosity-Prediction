# Porosity Prediction using Data Science Techniques
This project demonstrates how data science techniques can be used to predict porosity in subsurface geological formations. The data used in this project is synthetic, but the techniques demonstrated can be applied to real-world data.

# What is Physics-Based apprach ?
Physics-based and data-driven approaches have been traditionally viewed as two distinct approaches in scientific research. However, in recent years, there has been a growing interest in combining these two approaches to create more powerful and accurate models. 

Physics-based approaches rely on fundamental physical principles to model and simulate natural phenomena. These models are typically based on mathematical equations that describe the behavior of the system being studied. On the other hand, data-driven approaches use machine learning algorithms to analyze large datasets and identify patterns and relationships in the data. These models are based on statistical relationships between input and output variables and do not rely on any fundamental physical principles. The first is preferrerd in scientific reaserch while the latter is preferred in engineering. 

By combining physics-based and data-driven approaches, we can create models that leverage the strengths of both approaches. Physics-based models can provide insights into the underlying mechanisms governing the behavior of the system, while data-driven models can provide accurate predictions based on observed data. By combining these two approaches, we can create a model that leverages the physics-based understanding of fluid flow through porous media, while also incorporating the statistical relationships observed in the data. 

For example, we used our knowledge in reservoir properties in order to bound the porosity values that the model can predict. 

In summary, physics-based and data-driven approaches can be combined to create more powerful and accurate models. By leveraging the strengths of both approaches, we can create models that provide insights into the underlying mechanisms governing the behavior of the system while also providing accurate predictions based on observed data.


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
