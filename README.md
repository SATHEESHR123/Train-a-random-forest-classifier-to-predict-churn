# Train-a-random-forest-classifier-to-predict-churn
Train a random forest classifier to predict churn .Evaluate the predictions using evaluation metrics to demonstrate how accurately the model has performed
This final task is focused on building the predictive model using the CSV file that Estelle has shared.

- The CSV file contains cleaned and engineered features for training a predictive model.
- Download the Jupyter notebook and CSV file and execute the provided cells in the notebook.
- These cells will load the data and create train and test samples.
- Splitting data into train and test samples is crucial for measuring model performance on unseen data.
- This step is vital in assessing how accurately the model predicts churn for new customers.
- Skeleton code for creating a random forest classifier is provided in the notebook.
- It is the user's responsibility to fill in the code details using the provided documentation.
- By setting values for parameters and fitting the model on training data, a churn prediction model is obtained.
- Evaluation of the model's performance is left to the user.
- Metrics such as accuracy, precision, and recall are used in the notebook for evaluation.
- Accuracy alone may not suffice; other metrics provide a more nuanced assessment.
- For instance, precision and recall help gauge the model's performance in classifying positive and negative cases accurately.
- After evaluation, it may be evident that the current feature set is inadequate for predicting churn accurately.
- It's typically the data scientist's responsibility to engineer features that improve prediction accuracy.
- A feature importance chart is generated to visualize which features were useful within the model.
- Notably, features like net margin and consumption over 12 months are deemed important.
- However, price sensitivity features are scattered and do not emerge as primary churn drivers in their current form.
