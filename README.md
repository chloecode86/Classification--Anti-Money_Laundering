# Classification Project
>### AML Prediction <br />

#### Business Objective
To detect money laundering based on various features.

#### Data Collection
The dataset is obtained from Kaggle. <br /> 
<br />
• Time and Date
• Sender and Receiver Account Details
• Amount
• Payment Type (eg. credit card, debit card, cash, ACH transfers, cross-border, and cheque)
• Sender and Receiver Bank Location
• Payment and Receiver Currency
• 'Is Suspicious' Feature (Binary indicator)
• Type (Classifies typologies)

#### Models Evaluation
1. Naive Bayes <br />
   - Recall : 0.47 <br />
2. Logistic Regression <br />
   - Recall : 0.56 <br />
3. KNN <br />
   - Recall : 0.96 <br />
4. SVC <br />
   - Recall : 0.97 <br />
 <br />

Since the cost of not detecting true money laundering cases (false negatives) is high, Recall (also known as Sensitivity or True Positive Rate) is the most important metric for evaluation. SVC model has given the best result.
