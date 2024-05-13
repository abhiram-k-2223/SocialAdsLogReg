# Logistic Regression Classification Example

This repository contains a Python script implementing logistic regression for a classification problem using a dataset from Kaggle. 

## Dataset
The dataset used in this example is named "Social_Network_Ads.csv". It includes information about individuals' age, estimated salary, and whether they purchased a particular product. 

## Requirements
- Python 3.x
- Libraries:
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn

## Setup
1. Clone the repository or download the script.
2. Make sure all required libraries are installed (`pip install pandas matplotlib seaborn scikit-learn`).
3. Download the dataset "Social_Network_Ads.csv" from Kaggle and place it in the same directory as the script.

## Usage
1. Run the Python script.
2. The script reads the dataset, selects relevant columns (Age, EstimatedSalary, Purchased), and prepares the data for training.
3. It splits the data into training and testing sets using a 80-20 split ratio.
4. Standard scaling is applied to the features using `StandardScaler` from scikit-learn.
5. Logistic Regression model is trained on the training data.
6. The trained model is used to make predictions on the testing data.
7. Finally, the accuracy score of the model is calculated and printed.

## Acknowledgments
- Dataset source: [Kaggle - Social_Network_Ads](https://www.kaggle.com/rakeshrau/social-network-ads)

## Notes
- This example focuses on logistic regression as a simple classification algorithm, suitable for beginners in machine learning.
- Feel free to experiment with other algorithms or feature engineering techniques to improve the model's performance.

