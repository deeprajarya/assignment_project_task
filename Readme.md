## Assignment

Machine Learning model that predict the probability that a piece of text belongs to a particular class using techniques Bag of Words, tf-idf vectorization and word embedding.


Following steps are performed on the dataset

* EDA
* Feature Engineering
* Model Building

file : model_training.ipynb 
- This file include data collection, EDA, Feature Engineering and Model Training.
- Amoung decision tree, random forest and xgboost, random forest found as best model.
- The best model was saved as best__model.pkl file for further uses.

file : prediction.ipynb
- This file include prediction on unseen data using best_model.pkl file. 
- Before prediction required prepocessing was done on this unseen data.
- Prediction results are saved in 'Prediction.csv' file.

In model building stage 3 classification models are trained :
* Decision Tree
* Random Forest
* XGBoost

