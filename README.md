The data is dedicated to classification problem related to the post-operative life expectancy in the lung cancer patients: class 1 - death within one year after surgery, class 2 - survival.
After checking the outliers and null values and handle them, I replace string values to number so thee models can train on the dataset correctly
I checked the relation between features and the target column  using heatmap to do feature selection step.
Then I trained four individual models (Random Forest, Logistic regression, Decision Tree and Support vector machine) 
Then I created 3 ensembles model (Voting classifier, Bagging classifier, ADABoost classifier)
