 The files are structured as follows:
 - 'Prudential_Life_Insurance_DataVisualization.ipynb': jupyter notebook to visualize the dataset characteristics;
 - 'Prudential_Life_Insurance_Modeling.ipynb': jupyter notebook for preprocessing, modeling and performance evaluation stages;
 - 'Prudential_Life_Insurance_Testing.ipynb': jupyter notebook to test the best model on new data;
 - 'model.save': serialized best model;
 - 'Prudential_Life_Insurance_train.csv': train set;
 - 'Prudential_Life_Insurance_test.csv': test set;
 - 'Prudential_Life_Insurance_results.csv': submission file that contains the tuples ('Id', 'Response') for each 'Id' in the test set;
 - 'requirements.txt': file with the libraries used in the project.

 To assess the performance of the best model without having to run the whole training notebook, the pickle library was used to serialize and save it. 
