# Heart-Disease-ML
This is a project to see how various ML models classify heart disease and see which one performs the best.
The Machine Learning models used are Linear Regression/Classification, Support Vector Machines (SVMs), Decision Trees and Neural Networks.

In the future, would also want to try out other ML models such as XgBoost and Neural Networks in PyTorch and TensorFlow.

## About the Data
This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 14 attributes, including the predicted attribute. The "result" field refers to the presence of heart disease in the patient.

Attribute Information:
1. age
2. sex
3. chest pain type (4 values)
4. resting blood pressure
5. serum cholestoral in mg/dl
6. fasting blood sugar > 120 mg/dl
7. resting electrocardiographic results (values 0,1,2)
8. maximum heart rate achieved
9. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment
12. number of major vessels (0-3) colored by flourosopy
13. thal: 0 = normal; 1 = fixed defect; 2 = reversable defect


## Results
Comparing all the models, the model with the best performance was the Support Vector Classifier with a Linear kernel. This model achieved an overall accuracy of 91.7% (and average precision 0.92 and average recall 0.92).
The Decision Tree with Gini and max depth of 3 also performed quite well, with an overall accuracy of 85%.
