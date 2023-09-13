# Iris Flower Classification ML Project

## Steps to build a ML model
### Step 1: Importing the Dataset
- Import the Iris dataset from a CSV file.
- Explore the dataset by displaying the first 10 rows and checking for missing values.

### Step 2: Visualizing the Dataset
- Visualize the data using box plots to understand feature distributions.
- Create a heatmap to visualize feature correlations.

### Step 3: Data Preparation
- Remove the 'Id' column as it's not relevant for classification.
- Map species names ('Iris-setosa', 'Iris-versicolor', 'Iris-virginica') to numerical values (1, 2, 3) for classification.
- Split the dataset into feature variables (X) and the target variable (y).

### Step 4: Training the Algorithm
- Split the data into training and testing sets using `train_test_split`.
- Train a Linear Regression model on the training data.
- Evaluate the model's performance using the `model.score` method.

### Step 5: Making Predictions
- Use the trained model to make predictions on the test data.

### Step 6: Model Evaluation
- Calculate the mean squared error to assess the model's accuracy.
