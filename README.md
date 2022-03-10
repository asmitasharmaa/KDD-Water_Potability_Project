## Water Potability Prediction
By: Asmita Sharma and Pranshul Lakhanpal 

## Summary Statement

“Water, water everywhere but not a drop to drink.” India is a vastly populated country and water is a very precious resource. Having access to clean and safe drinking water is a basic right but not everyone has access to it. Contaminated water is a cause of a plethora of diseases like typhoid, cholera, etc that cause a lot of health concerns.

Our project aims to analyze and predict water quality based on the different parameters. We will visually be analyzing our data and we will be predicting if the water is safe to drink or not using different water quality metrics. We are using this dataset to perform our analysis and predictions.

Since our data is composed of numerical data, we will be using Linear Regression models, K-Nearest Neighbor classification, and Gradient boosting models to predict if the water is safe to drink. We chose these models because they tend to work better with numerical data classification and are very versatile to hyper-parameterization. 

We will be developing a metric to fill in the missing data points as well. And we would use feature importance to determine which data points help the model to provide better results.  If time permits, we would also like to do hyperparameter tuning to further improve the accuracy of our model's prediction. The data processing, model performance and accuracy, and project results will be consolidated into a presentation.


## Specific Aims

Finding which model fits best with numerical data to predict water potability
We think that Gradient Boosting would be the best performing model out of them all because it accounts for overfitting.

If we bin the data, will that improve or drop the performance of our models?
We want to experiment if this has any effect on our model's prediction. We believe that the model should have a slight increase in our model’s performance.

What fine-tuning can we do to increase the accuracy of our model? 
We can change different parameters for each model, some of the most prominent features that could be changed are the numbers of neighbors for the KNN model or the tree depth for the gradient boosting model.

Which features are the most dominantly used by our models when making a prediction?
It is hard to tell which feature would be the most dominantly used while making predictions by just looking at the data but we feel like the pH, Hardness, and Turbidity will be the most important features while determining the potability of the water.


## Team Outline

Asmita Sharma:
Cleaning data and filling in missing values
Making a KNN model (inbuilt and self-implemented)

Pranshul Lakhanpal:
Initial analysis of data
Making a Linear Regression model (inbuilt and self-implemented)

Common Work:
Calculating feature importance
Making a Gradient Boosting model (inbuilt and self-implemented)
Data analysis and visualization
Stretch Goal: Hyper Parameter tuning
Comparing the performance of models and consolidating results
Working on the presentation


## Timeline

Week 1: Cleaning and transforming data as per the requirements

Week 2: Implementing the KNN model and Linear Regression model; Training and testing the models

Week 3: Implementing the Gradient Boosting model; Training and testing the models

Week 4: Work on data visualization, analyze and compare results from all 3 models to predict water quality and drinkability

Week 5: Create the slides and deliver a presentation


## Final Deliverable
The data processing, model performance and accuracy, and project results will be consolidated into a presentation that we will be doing at the end of the quarter. We will also be submitting an IPython Notebook with all the code we wrote for this project.





