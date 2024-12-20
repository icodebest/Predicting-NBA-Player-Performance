# NBA Player Performance Prediction

This project focuses on building **Linear Regression** and **Ridge Regression** models to predict NBA player performance. Below is a summary of the steps undertaken in the project:

## Steps Performed

### 1. **Data Loading and Inspection**
   - The dataset was obtained from Kaggle and loaded for analysis. The features of the dataset were thoroughly examined to understand their structure and relevance.

### 2. **Data Preprocessing**
   - **Data Cleaning**: Irrelevant features were identified and removed based on their lack of contribution to the prediction of the output feature.
   - **Handling Missing Values**: Missing values were appropriately handled to ensure a clean and reliable dataset for model training.

### 3. **Feature Scaling**
   - **Standard Scaling** was applied to normalize all the features, ensuring that the data has a consistent scale for better model performance.

### 4. **Splitting the Data**
   - The dataset was divided into training and testing sets using an 80-20 split, which helped ensure that the model was evaluated on unseen data.

### 5. **Model Building**
   - **Linear Regression**: A basic linear regression model was developed and trained using the training data.
   - **Ridge Regression**: A ridge regression model with a default alpha value of 1.0 was trained to mitigate overfitting by applying regularization.

### 6. **Model Evaluation**
   - Both models were evaluated using the following metrics:
     - **R-squared**: This metric measures the proportion of variance in the target variable that is explained by the model.
     - **Mean Absolute Error (MAE)**: This metric evaluates the average magnitude of errors in the model's predictions.

### 7. **Results Visualization**
   - Visualizations were created to compare **Actual vs Predicted** values for both models.
   - **Residual plots** were generated to assess model performance and identify any systematic errors.

### Conclusion

Both the **Linear Regression** and **Ridge Regression** models exhibited similar performance, providing comparable results in terms of R-squared and Mean Absolute Error. These models offer a strong basis for predicting NBA player performance.


## How to Run the NBA Player Performance Prediction Project

Follow the steps below to set up and run this project on your local machine:

## 1. **Clone the Repository**
   - First, clone the repository to your local machine using the following command:
   ```bash
   git clone <https://github.com/icodebest/Predicting-NBA-Player-Performance> 
