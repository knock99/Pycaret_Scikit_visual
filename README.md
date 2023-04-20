# Pycaret_ScikitLearn
This project uses Pycaret to create three models using the Heart Disease data from UCI. It created the Light Gradient Boosting Machine model which I ended up selecting and tuning. The Extra Trees Classifier model and the Random Forest Classifier	model. The model ended up being over fit with my unseen data which was about 15% of the set. It was very over fit having scores of 1.00 for predicting if the person was postivie or negative for heart disease. This was likely caused by the size of the data set. The second part of the notebook scikitlearn metrics were imported along with seaborn to create a confusion matrix and heat map. Using the false postives and negatives which are at the core of the confusion matrix. This showed the same visual as the Pycaret confusion matrix where the scores were perfect with no false negatives or positives. The csv file of the UCI data used is posted above.
