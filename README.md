# InternIntelligence_Hyperparameter_tunning_task1
The code performs hyperparameter tuning for a Random Forest Classifier using Optuna on the Iris dataset. It begins by installing Optuna and importing necessary libraries like Scikit-Learn, Pandas, and NumPy. The Iris dataset is loaded and converted into a DataFrame (x) with target labels (y). An objective function is defined for Optuna, where it suggests different hyperparameters (n_estimators, max_depth, min_samples_split, and max_features) and evaluates the model using 5-fold cross-validation to maximize accuracy. The study is set up to maximize accuracy over 30 trials. After tuning, the best hyperparameters and accuracy are printed. The dataset is then split into training (80%) and testing (20%), and a new Random Forest model is trained using the best-found parameters. The model is evaluated on the test set, and the final accuracy is displayed. This approach efficiently finds optimal hyperparameters to improve model performance. 








