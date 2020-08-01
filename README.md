# back_pain
classification 
This dataset has 310 observations with 12 continuous variable and one categorical variable. Dependent variable has two features as abnormal and normal. As this is a healthcare dataset, recall should be greater than precision. That mean's we have to reduce false negative to increase recall. In the confusion matrix TN is greater than TP which is a good sign. The intuition behind this explains that actually predicted is abnormal and predicted outcome is also abnormal.
As Logistic Regression cannot work with categories we have to create dummy feature for encoding the target variable.
Accuracy of the model is 88%
