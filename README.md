# Iris-Data-Set-Logistic-Regression
This project utilizes the Iris dataset to perform logistic regression for the classification of iris flowers into three species: setosa, versicolor, and virginica. The primary goal is to build a predictive model that can accurately classify iris flowers based on their features.

## Datasets
The dataset used is the Iris dataset, which is a classic dataset in machine learning. It contains 150 samples of iris flowers with four features each (sepal length, sepal width, petal length, and petal width) and a target label representing the flower species.

- **Source**: The dataset is available in the `sklearn.datasets` module.
- **Preprocessing**: The dataset is clean and does not require preprocessing. It is directly loaded and used for training and testing the model.

## Methodology
1. **Data Loading**: The Iris dataset is loaded using `sklearn.datasets.load_iris()`.
2. **Data Exploration**: Descriptive statistics and correlation matrix are computed using pandas.
3. **Feature Engineering**: The features are extracted and a new column for the target variable is added to the DataFrame.
4. **Model Selection**: Logistic Regression is chosen for this classification task.
5. **Model Training**: The data is split into training and testing sets (67% training, 33% testing) and the logistic regression model is trained on the training set.
6. **Model Evaluation**: The model's performance is evaluated using accuracy score and classification report, which provides precision, recall, and F1-score for each class.

## Usage
1. **Run the script**: Execute the script to load the data, train the model, and evaluate its performance.
2. **Dependencies**: Ensure you have `pandas`, `sklearn` installed in your Python environment.
3. **Results**: The output includes descriptive statistics, a correlation matrix, and a classification report indicating the model's performance.

## Conclusion
This project demonstrates the application of logistic regression to classify iris flowers, showcasing fundamental machine learning techniques including data exploration, model training, and evaluation.
