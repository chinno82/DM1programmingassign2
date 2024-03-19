In this programming assignment you will be focusing on implementing classification methods and assessing their effectiveness using the dataset from Assignment 1. 
The main goal of this task is to gain experience, in utilizing machine learning techniques, data preprocessing, evaluating models and comparing classification algorithms.

Key Goals:
1. Implementing Classification Methods;
Use the Scikit learn library to apply six classification methods; Naive Bayes Classifier (GaussianNB) Support Vector Machine (SVM) with LinearSVC Decision Tree with DecisionTreeClassifier (max depth=10) Neural Network with MLPClassifier (3 layers of 10 nodes each) Random Forest with RandomForestClassifier and Adaboost with AdaBoostClassifier.
  
2. Data Preprocessing:
Utilize images from all four classes in the dataset.
Convert these images into edge histograms to represent them as vectors effectively.
Divide the dataset into training and test sets following an 80/20 ratio, for each class.
Standardize the training dataset to normalize the data.
Apply the standardization process (using means and variances calculated from the training dataset) to the test dataset.

3. Model Selection:
Conduct standard 5 cross validation and stratified 5 cross validation on the training set for model assessment purposes.Try out values, for k in the k Nearest Neighbor Classifier, such as 1, 3 5 7, 10 and 20. Plot the error curves (mean validation/training error versus k) to analyze the model complexity find the k value. Identify any signs of overfitting or underfitting.

Performance Comparison:
Perform a 5 cross validation on the classification problem with four classes using the specified classification methods. Create confusion matrices for each method on the test set to visualize how well they classify.
Compare the methods visually by examining the values in confusion matrices and their overall performance.
Calculate validation accuracies accuracies on the test set and F measure for each method to quantitatively compare their performance.

Instructions:
Setting Up Environment:
Clone this repository to your machine.
Install Python along with libraries like Scikit learn.
Utilize a Jupyter Notebook or any Python IDE for coding and running code.

Execution:
Open the provided Jupyter Notebook or Python script.
Follow the guidelines and comments, within the code to complete each task step by step.
Ensure that you appropriately reference and give credit when utilizing code or resources.

Additional Resources
For information, on Scikit learn visit; https;//scikit learn.org/stable/user_guide.html
To explore the Python programming language further check out; https;//www.python.org/
