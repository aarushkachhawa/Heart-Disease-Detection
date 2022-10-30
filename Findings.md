| [Home](./README.md)       | [Datasets](./Datasets.md)       | [Data Analysis](./DataAnalysis.md)      | [Machine Learning Models](./MLModels.md)      | [Results](./Findings.md)         |

# Results

The table below provides a detailed performance metrics comparison amongst the models. 
<img width="580" alt="Screen Shot 2022-10-29 at 9 01 26 PM" src="https://user-images.githubusercontent.com/61631006/198861976-3a40a5c5-5412-404a-8bf6-9e76a4f8e6ea.png">
+ The best performance was found in the **Random Forest** model with 94% accuracy, F1 score, precision and recall and 0.98 AUC value.
+ For the **Gradient Boosting** model, the best prediction accuracy of 94% for the test set was found to be with learning rate 0.5, the number of boosting stages of 300 and subsample of 0.5.
+ The **Artificial Neural Network** model had a classification accuracy of 91%
+  In the **Logistic Regression model**, a regularization parameter (penalty) of 12 and C parameter (penalty strength) of 1.0 were found to be most optimal resulting in accuracy of 79%.
      
      
      <img width="708" alt="Screen Shot 2022-10-29 at 8 51 47 PM" src="https://user-images.githubusercontent.com/61631006/198892834-df61ff1a-d6ea-4caa-85f2-44f6745231c4.png">
This figure illustrates the ROC curves for all the classification models in this study

# Conclusion 

On a merged dataset of over 700 patients from the UCI machine learning repository, the most accurate model was found to be the random forest classifier, showing an accuracy and F1 score of 94% and AUC of 0.98. It was found that ensemble learning methodologies along with data optimization and hyperparameter tuning techniques were able to achieve higher accuracy relative to prior published studies on these datasets. 
