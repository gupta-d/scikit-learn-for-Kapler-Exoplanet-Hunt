# scikit-learn-for-Kapler-Exoplanet-Hunt
We will use an ensemble of scikit-learn classification models to learn from Kapler data and predict the disposition of Kapler objects in Nasa Exoplanet Archive.
Models used for analysis are <b> KNN, Random Forests, MLP(neural Network), SVM.</b>

<b>`Accuracy Score, f1 Score and confusion matrix`</b> have been used in the code to evalue the model performance and determine our model of choice.

We will find which model works better with our data and then fine tune the hyperparameters with <b>GridSearch</b>.
We will also use <b>Recursive Feature Elimination</b> to determine if we could optimize the number of features to be used. 
