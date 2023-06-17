# Boston_House_Price_Prediction_ML_project
# Price Prediction with Boston Housing Dataset

This code performs price prediction using the Boston Housing dataset. The dataset contains various attributes of houses in Boston, along with their corresponding prices.

## Steps to Run the Code

1. Make sure you have the necessary libraries installed. The code requires `sklearn`, `pandas`, `matplotlib`, and `joblib`. You can install them using pip:
   ```
   pip install scikit-learn pandas matplotlib joblib
   ```

2. Download the `Boston_House_project.csv` file and place it in the same directory as the code file.

3. Run the code in a Python environment, such as Jupyter Notebook or any Python IDE.

4. The code will perform the following steps:

   - Load and explore the dataset, including data visualization and correlation analysis.
   - Split the dataset into training and test sets.
   - Handle missing attributes using different techniques.
   - Prepare the data for training by creating a pipeline for data transformation.
   - Select a regression model (Random Forest in this case) and train it.
   - Evaluate the model's performance using root mean squared error (RMSE) and cross-validation.
   - Save the trained model using joblib for future use.
   - Test the model on the test set and calculate the final RMSE.
   - Use the saved model to make predictions on new data.

5. The code also includes a section to demonstrate how to load the saved model and make predictions on new data. You can modify the `features` variable with your own data to get predictions.

## Additional Notes

- The code uses machine learning techniques to predict housing prices based on the given attributes. It trains a regression model on the training set and evaluates its performance using RMSE and cross-validation. The final trained model can then be used for making predictions on new, unseen data.

- The code includes various data preprocessing steps, such as handling missing values and creating a pipeline for data transformation. These steps are essential to ensure the model receives clean and standardized input data.

- The code saves the trained model using the joblib library. This allows you to persist the model and load it later for making predictions without retraining.

- The Boston Housing dataset used in this code is a well-known benchmark dataset in machine learning. It contains 13 input attributes (features) and a target variable (price) for predicting housing prices.

- You can customize and modify the code according to your specific requirements, such as trying different regression models, changing the evaluation metrics, or exploring different data preprocessing techniques.

- Feel free to refer to the code and the generated readme file for a better understanding of how to perform price prediction using the Boston Housing dataset.
