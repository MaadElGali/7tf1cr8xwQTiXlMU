# 7tf1cr8xwQTiXlMU
Predicting Customer Subscription to Banking Term Deposit 
Description:
The data comes from direct marketing efforts of a European banking institution. The marketing campaign involves making a phone call to a customer, often multiple times to ensure a product subscription, in this case a term deposit. Term deposits are usually short-term deposits with maturities ranging from one month to a few years. The customer must understand when buying a term deposit that they can withdraw their funds only after the term ends. All customer information that might reveal personal information is removed due to privacy concerns.
Attributes: age (numeric), job (categorical), marital (categorical), education (categorical), default (binary), balance (numeric), housing (binary), loan (binary), contact (categorical), day (numeric), month (categorical), duration (numeric), campaign (numeric, includes last contact) Output (desired target): y (binary)
I built a ML model using Random Forest to predict if the customer will subscribe (yes/no) to a term deposit (variable y)
Success Metric(s):
I was able to hit %93 accuracy by evaluating with 5-fold cross validation and reporting the average performance score.
