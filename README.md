# credit-risk-classification report
## Analysis Overview
The analysis is intended to test whether Sklearn Logistic Regression Model is adequate to provide a prediction of the risks of the loans. Data that are used are a generated dataset of historial lending activity from a peer-to-peer lending service company.(The dataset is generated by edX Boot Camps LLC.)
The dataset is separated randomly into a testing dataset and a training dataset using the train_test_split() function from the Sklearn library.
For the evaluation of the analysis, confusion_matrix() and classification_report() functions from Sklearn are used. 
<br>
## Result
* Precision Score of healthy risk(0): 0.99 <br />
  A relatively high precision score, which means that the model is very good at predicting borrowers with healthy loan risk.
* Precision Score of high risk(1): 0.91 <br />
  A relatively good precision score, which means that the model is good at predicting borrowers with high risk loan borrowers.
* Recall Score of healthy risk(0): 1.00 <br />
  A almost perfect recall score, which means that the model retrieves almost all healthy risk loan borrowers.
* Recall Score of high risk(1): 0.85 <br />
  A reltively decent recall score, wich means that the model is likely to retrieves 85% of the high risk loan borrowers.
* Accuracy: 0.99 <br />
  The accuracy score tells us that the model is at approximately 99% at prediction the loan risk of borrowers.
<br>
Screenshot of Classification report using Sklearn classification_report() function:<br />
![Alt text](https://github.com/henrychan990805/credit-risk-classification/blob/a7210824502251aba713e60b88f5ac44fa90d18b/Result/classification_report.png)<br />
Screenshot of Confusion Matrix using Sklearn confusion_matrix() function:<br />
![Alt text](https://github.com/henrychan990805/credit-risk-classification/blob/a7210824502251aba713e60b88f5ac44fa90d18b/Result/confusion_matrix.png)
<br>
