This work is used to create a submission for the "Titanic: Machine Learning from Disaster" Kaggle competition (https://www.kaggle.com/c/titanic). The goal of the competition is to most accurately predict the survival of Titanic passengers given various feature data for each passenger. Passenger data includes 10 features describing age, ticket class, fare, etc.

The data is imported, cleaned, and processed before a logistic regression model is used to make predictions. The method's hyperparameters are chosen using grid- and randomized-searches with cross-validation.

Per the Kaggle evaluation details: "Your score is the percentage of passengers you correctly predict." Upon submission, the passenger survival predicted by this model received a score of approximately 0.75. As of 2018-08-19, the fiftieth-place score is approximately 0.91.

