Predict Bike Sharing Demand with AutoGluon 


## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: While predicting values,for the give datasets,i observed that there is effect of time_limit,presets on predictions(output).To get a better accuracy for the model changing the parameters epoches,time_limit,boost rounds had a signficant impact on output.

### What was the top ranked model that performed? [Iam facing a problem with intrepetor]
TODO: Add your explanation

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: By performing EDA,it was observed that most of features like humudity,atemp has least effect on target variable,this was observed via heatmap.Considering hours in day,is new feature.Considering the average of day,years,month is a bad way of evalutation.
For example - on a rainy day,there will more numbers of bike will be rented compared to a sunny day.Only in peak hours.

### How much better did your model preform after adding additional features and why do you think that is?
TODO: Additional features of hours,will defiently increase the sorce based on hypothesis gathered from EDA.

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: According to the theortical knowledge,changing the parameters will have direct effect on output(target variable)

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: On EDA,because it's step where you can analysis dataset,clearly,and form a hypothesis.EDA gives us insights about the different variables have a connectivity with target variable.

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
Kindly check my project notebook.I have written my code,but there was problem with the intrepter so i was able to complete 50% of the problem.
### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Facing an issue with the interpter.So i was unable to complete the last 2 steps(6,7).

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Facing an issue with the interpter.So i was unable to complete the last 2 steps(6,7).

## Summary
TODO: Working with AWS Sagemakers was itself a new experience.It was very handy to perform the most complex task in a simplfied manner.I learned new tools such as AutoML,Xgboost,AutoGluon.Data cleaning,EDA are the important stages in ML Life cycle.
