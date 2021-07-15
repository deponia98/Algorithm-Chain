# Titanic Dataset

The titanic datasets consists of 9 columns as follows:
* sex: gender of the passenger
* age: age of the passenger
* parch: number of parent(s) or children(s)
* fare: the fare price of the ticket
* class: the class of the passenger
* deck: the deck location of the passenger in the ship
* embark town: the embark location of the passenger
* alive: describe whether the passenger is alive or not in the titanic incident
* alone: describe whether the passenger is alone or not

Using this dataset, the notebook shows machine learning algorithm chain with details as follows:
* the target is to predict whether an upcoming passenger will be alive or not if the same incident occurs again in the future
* the preprocessing steps consists of imputing missing values and encoding categorical features (there is an additional scaling step for KNN model)
* machine learning model tested: Logistic Regression, Decision Tree, KNN
* hyperparameter tuning is conducted for the chosen model from above
