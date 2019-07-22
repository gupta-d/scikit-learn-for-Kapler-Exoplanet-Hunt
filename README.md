# scikit-learn-for-Kapler-Exoplanet-Hunt
We will use an ensemble of scikit-learn classification models to learn from Kapler data and predict the disposition of Kapler objects in Nasa Exoplanet Archive.

To start with we loaded data to pandas dataframe did initial analysis,  dropped irrelevant features, handeled Nulls and scaled the data before fetching to classification models.

Models used for our analysis are <b> SGD, linearSVC, KNN, Random Forests, MLP(Neural Network).</b> Performance of these models with mostly default hypermeters is as below:

![Screenshot-1](/CV_performance_of_various_models_using_train_data.PNG)

based on above performance, we selected Random Forests, KNN and MLP<b> for further optimization and testing with test data. We will fine tune the hyperparameters with <b>GridSearch</b>.
`Accuracy Score, f1 Score and confusion matrix`</b> have been used to evalue the model performance and determine our model of choice. 

Finally we will also use <b>Recursive Feature Elimination feature of scikit-learn </b> to determine if we could optimize the number of features to be used. 

Random Forest emerges as best model for our dataset, achiving an accuracy of 0.883.
