# CCF_AISOC
This project involves creating models to identify fraudulent transactions based on patterns observed in transaction data using Logistic Regression. During training, the model learns patterns and relationships in the data that distinguish fraudulent activities. The process involves the following steps:
-The dataset is loaded into a Pandas DataFrame, and its structure, missing values, and class distribution (whether the transaction is legitimate vs. fraudulent transactions) are examined.
-Transactions are separated into legitimate and fraudulent categories. Statistical summaries are computed, and the dataset is balanced by undersampling legitimate transactions to match the count of fraudulent transactions.
-Features (transaction details) and the target variable (transaction class) are separated for analysis.
-Class column indicating transaction type 
   **0: legitimate**
   **1: fraudulent**
-The data is split into training and testing sets, ensuring class balance with stratified sampling.
-A Logistic Regression model is trained using the training dataset.
-The model's performance is evaluated using accuracy scores on both training and testing data.
     Accuracy according to Training data: 93%
     Accuracy according to Testing data: 94%
