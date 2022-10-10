# Project Title
## **Mushroom Classification**


# Aim of the Project
**In this Notebook I will be dealing with the Mushroom Classification by using Decision Tree Classifier using both Entropy and Gini Index.
For the first step of this notebook, I will work on the Exploratory Data Analysis of this dataset by using Seaborn, Matplotlib and Plotly libraries.
For the next step, I will deal with the missing data points (if they exist), and then encode the dataset for the data pre-processing step.
Finally, I will train Decision Tree Classifier Model using both Entropy and Gini Index.**

# Required Python Packages and Libraries
* Numpy
* Pandas
* Matplolib
* Seaborn
* Plotly
* Scikit-learn

# Dataset Used:
* mushrooms.csv - The dataset consists of the different features of mushrooms and its class which shows whether the mushroom is edible or poisonous.
* The Following project is made on python notebook file so make sure to download the dataset and load the dataset in the Jupiter notebook or google colab before running the project.
# Dataset link:
* Dataset can be downloaded from the following link - https://drive.google.com/file/d/1JADC6wnnU7Vn8d77fkWPBmp3RWFdZdUj/view?usp=sharing
# Project Link:
* Mushroom Classification.ipynb - This notebook file contains the complete project.
* Project can be downloaded from the following link - https://colab.research.google.com/drive/1y1Oz9Eg8_FI18JdOb3u-8sdDq5Pao-D4?usp=sharing

# Project Implementation:
* Performed Exploratory data analysis.
* Performed Visualization of the features of the mushrooms with respect to its class using matplotlib, seaborn and plolty libraries.

## Model Creation:
* Used Scikit learn library to implement the model.
* Splitted data into training and test data.

## Model Used:
* Classification model Decision Tree Classifier was used.
* Decision Tree was implemented on both criterions 
     * Entropy 
     * Gini Index
* **Decision Tree** - A Decision Tree is a predictive modeling approach. It is used to address classification problems. It is having a tree-like structure upside down and represents decisions or for decision-making. It can handle high dimension data and have good accuracy.Classifiers are used when the target variable is categorical. Entropy/Information gain or Gini Index can be used for choosing the best split. 
* **Entropy** - Entropy is a measure of disorder or impurity in the given dataset. In the decision tree, messy data are split based on values of the feature vector associated with each data point. With each split, the data becomes more homogenous which will decrease the entropy. However, some data in some nodes will not be homogenous, where the entropy value will not be small. The higher the entropy, the harder it is to draw any conclusion. When the tree finally reaches the terminal or leaf node maximum purity is added.
* **Gini Index** - The Gini index can also be used for feature selection. The tree chooses the feature that minimizes the Gini impurity index. The higher value of the Gini Index indicates the impurity is higher. Both Gini Index and Gini Impurity are used interchangeably. The Gini Index or Gini Impurity favors large partitions and is very simple to implement. It performs only binary split. For categorical variables, it gives the results in terms of "success" or "failure".

# Project Conclusion :
* Achieved F1 score of around 96%, which shows the great accuracy.
* Decision-Tree Classifier model using both gini index and entropy have only very very small difference in model accuracy and training set accuracy, so there is no sign of overfitting.
* Decision Tree shows the best results of Classifying the edible and poisonous mushrooms.
![result](https://user-images.githubusercontent.com/101913703/194864361-4fb8b72a-d9b0-41fe-a3a6-d47178be9ffd.png)
