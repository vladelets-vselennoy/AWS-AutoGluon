# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Raghuraj Pratap Yadav

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: i had to remove negtaive values

### What was the top ranked model that performed?
TODO:  WeightedEnsemble_L3

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: changed weather and season column to category and also added hours column

### How much better did your model preform after adding additional features and why do you think that is?
TODO: it scored very much better from 50 to 1.7 

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO:  not that much good my model performed

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: hyper parameter tuning. trying various configurations

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
|model|hpo1|hpo2|hpo3|score|
|--|--|--|--|--|
|initial|default|default|default|1.75354|
|add_features|default|default|default|0.73169|
|hpo|hpo|knn|rf|0.5375|

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](img/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](img/model_test_score.png)

## Summary
TODO: in terms of RMSE score added feature model performs better but in according to kaggle hpo model performed better
