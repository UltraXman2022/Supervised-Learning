<h1>Project description</h1>
Beta Bank customers are leaving: little by little, chipping away every month. The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones.
We need to predict whether a customer will leave the bank soon. You have the data on clients’ past behavior and termination of contracts with the bank.
Build a model with the maximum possible F1 score. To pass the project, you need an F1 score of at least 0.59. Check the F1 for the test set.
Additionally, measure the AUC-ROC metric and compare it with the F1.

<h2>Project instructions</h2>
<ul><li>Download and prepare the data. </li>
<li>Explain the procedure.</li>
<li>Examine the balance of classes. </li>
<li>Train the model without taking into account the imbalance. </li>
<li>Briefly describe your findings.</li>
<li>Improve the quality of the model. </li>
<li>Make sure you use at least two approaches to fixing class imbalance. </li>
<li>Use the training set to pick the best parameters. </li>
<li>Train different models on training and validation sets. </li>
<li>Find the best one. </li>
<li>Briefly describe your findings.</li>
<li>Perform the final testing.</li></ul>

<h2>Data description</h2>

Features
<ul><li>RowNumber — data string index</li>
<li>CustomerId — unique customer identifier</li>
<li>Surname — surname</li>
<li>CreditScore — credit score</li>
<li>Geography — country of residence</li>
<li>Gender — gender</li>
<li>Age — age</li>
<li>Tenure — period of maturation for a customer’s fixed deposit (years)</li>
<li>Balance — account balance</li>
<li>NumOfProducts — number of banking products used by the customer</li>
<li>HasCrCard — customer has a credit card</li>
<li>IsActiveMember — customer’s activeness</li>
<li>EstimatedSalary — estimated salary</li></ul>

Target
<ul><li>Exited — сustomer has left</li></ul>
