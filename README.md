# Capstone_2
Project using a kaggle dataset to try to predict individual's risk of heart disease
Dataset found here: https://www.kaggle.com/alexteboul/heart-disease-health-indicators-dataset
Heart disease is the leading cause of death for most groups in the United States.
This project looks at taking information from a yearly study the CDC conducts and tries to
use that information to determine if we can accuractely and meaningfully predict if an individual
is at risk.

I use several supervised learning techniques such as random forest, decision trees, svm, and boosting models
to try to get the best model for the dataset. Unfortunately, it turns out that while we can obtain >90%
accuracy for many of the models, that is due to the nature of the dataset (most people at a specific time
are not going to die of heart disease). However, this can still lead to future endeavors where we try it
with a different dataset or be used to encourage people to not try to self-diagnose, as turns out to be
a complicated problem.
