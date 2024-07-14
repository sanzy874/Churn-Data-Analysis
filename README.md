# Churn-Data-Analysis
Churn data was cleaned, analysed, visualized, models were implemented, and accuracy was checked.

--Analysis:
Decision Tree Classifier: 
Simple Train Test Splitting: Achieves an accuracy of approximately 91.11%. Precision, recall, 
and F1-score are also reasonable but slightly lower than the accuracy. 
K-fold Splitting k=10: Shows slightly improved performance compared to simple train-test 
splitting. Accuracy, precision, recall, and F1-score are all higher, indicating better 
generalization. 
K-fold Splitting k=3: Performance is similar to k=10 but with a slightly lower accuracy and F1
score. 
Naive Bayes Classifier: 
Simple Train Test Splitting: Achieves an accuracy of around 87.65%. However, precision, 
recall, and F1-score are lower compared to the decision tree classifier. 
K-fold Splitting k=10 and k=3: Both show similar performance, with accuracy around 
86.22%. The precision, recall, and F1-score are consistent with the simple train-test splitting. 
KNN Classifier: 
Simple Train Test Splitting: Shows an accuracy of approximately 88.40%. Precision is 
relatively high, but recall is lower, indicating potential issues with false negatives. 
K-fold Splitting k=10 and k=3: Both exhibit similar performance with accuracy around 
88.03% to 88.04%. Precision and recall are consistent with the simple train-test splitting. 

--Conclusion: 
Decision tree classifiers generally perform better than Naive Bayes and KNN classifiers in 
terms of accuracy, precision, recall, and F1-score across all splitting methods. 
K-fold splitting, particularly with k=10, tends to provide slightly better performance metrics 
compared to simple train-test splitting, indicating better model generalization. 
Naive Bayes classifiers show the lowest performance among the three classifiers, especially 
in terms of precision and recall, suggesting that it may not capture the underlying patterns in 
the data as effectively as decision tree and KNN classifiers. 
In conclusion, based on these results, the decision tree classifier with k-fold splitting (k=10) 
appears to be the most suitable model for this dataset considering both accuracy and 
other evaluation metrics.
