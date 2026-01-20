# Sampling-repo
Sampling Assignment Submission - Aditvir Rinwa - 102317150

## Methodology

The given dataset is highly imbalanced, where fraudulent transactions are very few compared to normal transactions.
To handle this issue, the dataset was first balanced using SMOTE so that both classes have equal representation.

After balancing, five different samples were created from the dataset.
Five sampling techniques were then applied:
Random Undersampling, Random Oversampling, SMOTE, NearMiss, and SMOTE with Tomek Links.

For each sampling technique, five machine learning models were trained:
Logistic Regression, Decision Tree, Random Forest, KNN, and SVM.
The dataset was split into training and testing sets, and accuracy was calculated for comparison.

## Result Table

The result table shows the accuracy of each machine learning model for every sampling technique.
It can be observed that different models respond differently to different sampling methods.
Some models perform better with undersampling, while others benefit from oversampling or hybrid methods.

## Result Graph

A bar graph is used to visually compare the accuracy values obtained from different sampling techniques.
The graph helps in understanding how the performance of models varies when the sampling strategy is changed.

## Conclusion

This experiment shows that there is no single best sampling technique for all models.
The choice of sampling method should depend on the machine learning model and the nature of the dataset.
This assignment helped in understanding the importance of sampling techniques when working with imbalanced data.

## Author
Aditvir Rinwa
