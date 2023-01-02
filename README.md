# Decision-Trees-and-kNN-for-Telecom-Churn-dataset
We'll apply the concepts of Decision trees and kNN to a Telecom company's churn dataset

Datasets for experimentation: telecom_churn.csv

Code and Analysis is in the file: Decision Trees and kNN.ipynb

We'll address the following questions to understand the concepts of the decision trees and kNN by appyting to this telecom churn dataset.
Answer the following questions:
1. Decision tree classifier sklearn.tree.DecisionTreeClassifier has the parameter "max_depth", which defines the maximum depth of the tree, and "criterion", which measures the quality of the split. What happens if we don't specify any value for both parameters?
2. For the synthetic dataset, we separate two classes by training a decision tree. What does the boundary look like when we overfit ( max_depth ≥ 4 ) and underfit (max_depth = 1) the decision tree on data? For both cases, paste the decision tree and the decision boundary from the Jupyter notebook output.
3. For Bank Dataset, what are the 5 different age values that the decision tree used to construct the tree? What is the significance of these 5 values?
4. Given a dataset d, with n samples and m continuous features, what does Standard Scaler sklearn.preprocessing.StandardScaler do? Given dataset d = [[0, 0], [0, 0], [1, 1], [1, 1]], write down its scaler transformation.
5. In the section Underfitting and Overfitting (Jupyter notebook), we have classified two datasets (a small one and a big one) using two different decision trees to demonstrate underfitting and overfitting. Briefly describe the experiments performed and what you learn from these experiments.
6. In section Imbalanced Class (Jupyter notebook) , we have trained a couple of classifiers on the balanced and unbalanced datasets and evaluated their accuracy on balanced and unbalanced datasets. Furthermore, we have printed the confusion matrix. Briefly describe the experiments performed and what you learn from these experiments. Also, write down the experiments' precision, recall, and f1 score.
7. In the section Adding irrelevant attributes (Jupyter notebook), we have added an irrelevant attribute to the dataset and have trained a decision tree classifier on it. Based on the test set results, what do you think has happened, and can you connect it with the class material? Briefly describe the experiment done and the intuition developed from these experiments.
8. For the customer churn prediction task, we show that the accuracy of the decision tree is 94% when max_depth is set to 5. What happens to accuracy when we leave the value of max_depth at its default value? Explain the rise/fall of accuracy.
9. How many decision trees do we have to construct if we have to search the two-parameter space, max_depth [1-10] and max_features [4-18]? If we consider 10-fold cross-validation with the above scenario, how many decision trees do we construct in total?
10. For the customer churn prediction task, what is the best choice of k [1-10] for the k-nearest neighbor algorithm in the 10-fold cross-validation scenario?
11. For MNIST dataset, what was the accuracy of the decision tree [max depth = 5] and K-nearest neighbor [K = 10]? What are the best parameters and accuracy for the holdout dataset for decision trees when we used GridSearchCV with 5-fold cross-validation?

Solution file for the above mentioned questions: Solutions_Decision Trees and kNN_Telecom_Churn.pdf 
