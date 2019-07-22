# scikit-learn-for-Kapler-Exoplanet-Hunt
We will use an ensemble of scikit-learn classification models to learn from Kapler data and predict the disposition of Kapler objects in Nasa Exoplanet Archive.

We also dropped irrelevant features, handeled Nulls and scaled the data before fetching to classification models.

Models used for analysis are <b> SGD, linearSVC, KNN, Random Forests, MLP(Neural Network).</b>

![Screenshot-1](/CV_performance_of_various_models_using_train_data.PNG)

<b>`Accuracy Score, f1 Score and confusion matrix`</b> have been used in the code to evalue the model performance and determine our model of choice. 

We will find which model works better with our data and then fine tune the hyperparameters with <b>GridSearch</b>.
We will also use <b>Recursive Feature Elimination</b> to determine if we could optimize the number of features to be used. 


Random Forest emerges as best model for our dataset, achiving an accuracy of 0.883.
