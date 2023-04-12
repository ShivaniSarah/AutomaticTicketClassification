# Automatic-Ticket-Classification-
Build a model that is able to classify customer complaints based on the products/services -  segregate customer tickets into their relevant categories and, therefore, help in the quick resolution of the issue.


# Problem statement
For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers. 

These customer complaints are unstructured text data; so, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. This becomes tedious as the company grows and has a large customer base.

In this case study, you will be working as an NLP engineer for a financial company that wants to automate its customer support tickets system. As a financial company, the firm has many products and services such as credit cards, banking and mortgages/loans. 

# Business goal
You need to build a model that is able to classify customer complaints based on the products/services. By doing so, you can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

With the help of non-negative matrix factorization (NMF), an approach under topic modelling, you will detect patterns and recurring words present in each ticket. This can be then used to understand the important features for each cluster of categories. By segregating the clusters, you will be able to identify the topics of the customer complaints. 

You will be doing topic modelling on the .json data provided by the company. Since this data is not labelled, you need to apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:

<li> Credit card / Prepaid card </li> 
<li> Bank account services </li>
<li> Theft/Dispute reporting </li>
<li> Mortgages/loans </li>
<li> Others </li>

With the help of topic modelling, you will be able to map each ticket onto its respective department/category. You can then use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, you can classify any new customer complaint support ticket into its relevant department.

# Dataset

down load the data set from this link https://drive.google.com/file/d/1Y4Yzh1uTLIBLnJq1_QvoosFx9giiR1_K/view

OR you may download the dataset added to this repo  https://github.com/santoshramakumar/Automatic-Ticket-Classification-/blob/563d92070d5e8b4a1ae90a91e0747224dc891129/complaints-2021-05-14_08_16.zip

The data set given to you is in the .json format and contains 78,313 customer complaints with 22 features. You need to convert this to a dataframe in order to process the given complaints.

# Tasks performed on dataset 

The following eight major tasks are performed, 

<li> Data loading </li> 
<li> Text preprocessing </li> 
<li> Exploratory data analysis (EDA) </li> 
<li> Feature extraction </li> 
<li> Topic modelling </li> 
<li> Model building using supervised learning </li> 
<li> Model training and evaluation </li> 
<li> Model inference </li> 
