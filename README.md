# Automatic Ticket Classification 
> We need to build a model that is able to classify customer complaints based on the products/services. By doing so, you can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

We will be doing topic modelling on the .json data provided by the company. Since this data is not labelled, We need to apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:

- Credit card / Prepaid card
- Bank account services
- Theft/Dispute reporting
- Mortgages/loans
- Others

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contributors](#contributors)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- With the help of topic modelling, we will be able to map each ticket onto its respective department/category. We can then use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, We can classify any new customer complaint support ticket into its relevant department.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Technologies Used
- Python Pandas - version 1.1.5
- Python Numpy - version 1.19.5
- Python Seaborn - version 0.11.2
- Sklearn
- en_core_web_sm
- nltk
- spacy
- swifter
- Jupyter Notebook - version 6.4.10
- ipykernel - version 6.13.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Conclusions
- Logistic regression is giving best accuracy on train and test data.
- Decision tree is highly overfitted model.
- Random forest and Naive bayes are not better than Logistic Regression.
- Even after hyper parameter tuning Random forest is not giving better accuracy than Logistic Regression.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Contributors
* [Shravan](https://github.com/simplyshravan)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
