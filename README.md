### Churn Prediction

### Introduction

This project was inspired by my time at Tesco CEC, where I worked with telephony data and Employee Absence Rate Data.
Tesco CEC generally deals with customer queries and complaints r.e. a number of Tesco products, such as Tesco Clubcard.
By providing good Customer Service via the telephone, Tesco would maintain a high Performance KPI.
BY providing a good service for customers, e.g., solving their problem efficiently, customers would be less likely to **churn**.
That is, leave Tesco and shop somewhere else.

<br>
This project is similar to the situation I described above, however, this is a hypothetical telecom company that offers phone and internet services. The problem: Some of the Customers are churning. For example, these customers are no longer using the services an. Obviously this is the last thing a company wants. To stop this from happening, a system will need to be developed to identify these customers and offer them an incentive to stay. The best way for customer retention will be to use promotional messages and offer discounts on products/services. Its also important to understand why these customers are churning. To answer that, the ability to interpret the model's predictions will be needed. 
<br />

### Data

**Note**: the dataset is open-source and be found [here](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

The dataset consists of:

* Services of the customers: phone; multiple lines; internet; tech support and extra services such as online security, backup, device protection, and TV streaming.
* Account information: how long they have been clients, type of contract, type of payment method.
* Charges: how much the client was charged in the past month and in total.
* Demographic information: gender, age, and whether they have dependents or a partner.
* Churn: yes/no, whether the customer left the company within the past month; this information is used as the **target variable in the Machine Learning Model**.

### Project Outline

* Download dataset and do some initial Data Processing.
* Split the data into train, validation and test, so the models can be validated.
* As part of the initial Data Analysis, look at feature importance to identify which features are important in the data.
* Transform categorical variables into numeric variables so they can be used in the model.
* Train a **Logistic Regression Model**.

The project is split into three main components:

* **Logistic Regression for Customer Churn**.
* **Evaluation of the Metrics used for Customer Churn**.
* **Deployment of the Logistic Regression Model for Customer Churn**.

### Tools

* `Python 3.7`. Thats what was used but any `Python 3.x` will be fine.
* `Jupyter Notebook`. Note: if you download `Anaconda`, `Jupyter Notebook` will come with it along with things like `Spider IDE`.
* Text Editor: I used `Sublime Text` on `Ubuntu 20.04`. Any will do. E.g. `MS Visual Studio Code`, 
* `scikit-learn` for the actual Machine Learning.


### Instructions


* `$ git clone https://github.com/MRLintern/churn_prediction.git && cd churn-prediction`
* `$ jupyter notebook`

You can copy/type in the code into cells and then run them. 

### TODO
* **Evaluation of the Metrics used for Customer Churn**.
* **Deployment of the Logistic Model for Customer Churn**.



