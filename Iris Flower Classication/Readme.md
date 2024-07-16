# Iris Dataset Analysis and Classification

This project demonstrates the process of loading, visualizing, and analyzing the Iris dataset, followed by training multiple classifiers and evaluating their performance. The following steps outline the entire process:

## Import Necessary Libraries
Libraries such as numpy, pandas, matplotlib, and seaborn are imported for data manipulation and visualization.

## Load the Dataset
The Iris dataset is loaded into a pandas DataFrame from a CSV file.

## Check the Statistics of the Dataset
Summary statistics for each feature (sepal length, sepal width, petal length, petal width) are displayed. The dataset consists of 150 entries with no missing values.

## Check the Description of the Dataset
Detailed statistics including count, mean, standard deviation, minimum, and maximum values for each feature are presented. No null values are detected in the dataset.

## Check for Duplicate Values
The dataset is checked for duplicate entries, and if found, duplicates are removed. The final dataset is evenly distributed among the three species: Iris-setosa, Iris-versicolor, and Iris-virginica.

## Visualize Relationships
Scatter plots are created to visualize the relationships between different pairs of features:
- **Sepal Length vs Sepal Width:**
  - Species Virginica has larger length but smaller width.
  - Species Setosa has smaller length but larger width.
  - Species Versicolor lies between Virginica and Setosa.
- **Petal Length vs Petal Width:**
  - Species Virginica has both larger length and width.
  - Species Setosa has smaller length and width.
  - Species Versicolor lies between Virginica and Setosa.

## Correlation Analysis
A heatmap is created to display the correlation between different features. Sepal length and sepal width show a negative correlation, whereas petal length and petal width show a strong positive correlation.

## Split the Dataset
The dataset is split into dependent (species) and independent variables (features). Further split into training and testing sets using `train_test_split`.

## Model Training and Evaluation
Several classifiers are used to train the dataset: Logistic Regression, Decision Tree, K-Nearest Neighbors, and Support Vector Classifier. Training and testing accuracies for each model are reported:
- **Logistic Regression:**
  - Training Accuracy = 0.95
  - Testing Accuracy = 1.0
- **Decision Tree Classifier:**
  - Training Accuracy = 1.0
  - Testing Accuracy = 1.0
- **K-Neighbors Classifier:**
  - Training Accuracy = 0.96
  - Testing Accuracy = 0.98
- **Support Vector Classifier:**
  - Training Accuracy = 0.96
  - Testing Accuracy = 1.0

## Confusion Matrix
A confusion matrix is generated to evaluate the performance of the classifiers on the testing set.

## Conclusion
The notebook successfully demonstrates the process of loading, visualizing, and analyzing the Iris dataset, followed by training multiple classifiers and evaluating their performance. The results indicate high accuracy for all models, with Decision Tree Classifier and Support Vector Classifier achieving perfect accuracy on both training and testing datasets.

This process can be replicated or modified for other similar classification tasks by following the steps outlined in the notebook.
