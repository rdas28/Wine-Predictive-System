Wine Quality Prediction

Overview

This project focuses on predicting the quality of red wine using machine learning techniques. The dataset used is winequality-red.csv, which contains physicochemical properties of different wines along with their quality ratings. The model employs a Random Forest Classifier to classify wine quality as either good or bad based on predefined thresholds.

Dataset

The dataset consists of multiple features representing the physicochemical properties of wine:

Fixed acidity

Volatile acidity

Citric acid

Residual sugar

Chlorides

Free sulfur dioxide

Total sulfur dioxide

Density

pH

Sulphates

Alcohol

Quality (target variable)

Installation

To run this project, you need to have Python 3.x installed along with the following dependencies:

pip install numpy pandas seaborn matplotlib scikit-learn

How to Use

Load the dataset: The script reads winequality-red.csv into a pandas DataFrame.

Data visualization: Various plots such as bar charts and heatmaps are used to understand data distribution and correlations.

Data Preprocessing:

Missing values are checked.

Label binarization is applied to classify wine quality as good (>=7) or bad (<7).

Features (X) and target variable (Y) are separated.

Model Training:

The dataset is split into training and testing sets (80%-20%).

A RandomForestClassifier is trained on the training data.

Model Evaluation:

The model's accuracy is calculated using the test set.

Prediction:

A sample input is tested to predict whether the wine is of good or bad quality.

Running the Script

Run the Python script using:

python winequality.py

After execution, the accuracy of the model is displayed, followed by the classification of a sample wine input.

Example Output

Accuracy: 0.87
Good Quality Wine

Contributors

Madhur Gusain

Riddhi Das

License

This project is open-source and available under the MIT License.


