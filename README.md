# Credit-Card-Fraud-Isolation-Forest-Algorithm
Comparing main stream supervised ML model to Isolation Forest Algorithm
In the age of digital world, credit card fraud is one of the most common yet very pervassive problem that affects many financial instutions as well as their clients. Its very important for banks and credit card companies to find this kind of transaction and flag them in timely manner and as acccurately as possible so that the proper actions can be taken.

About the data and workflow:
This is one of the most common data used by many data scientist and data enthausiast for many great works. Here I am taking an approach to compare a main stream supervised machine learning models to a lesser known machine learning algorithm such as Isolation Forest Algorithm.

I will first do some EDA of the dataset, some cleaning up and scaling when needed. Then I will run a base model to do some feature engineering and hyper parameter testing, work on balancing the imbalance class data (using Undersampling techniques) and then finally generate a classification based model preferably a Logistic Regression. I will then validate the model in the validation dataset and then come up with the final accuracy scores and AUC value.

Once the model is generated, I will then apply lesser known Isolation Forest Algorithm that has great potential, to work properly on this kind of imbalanced data without the need of under-sampling, over-sampling or synthetic sampling to balance the highly imbalanced datset(ratio of 99.83:0.17).

Fianlly I will make some comparision of the results and make some final comments.

The data is found in a Kaggle webpage and can be downloaded using following link: https://www.kaggle.com/mlg-ulb/creditcardfraud

This dataset contains the credit card transaction for 24 hours time period in September of 2013. The dataset contains only numerical values and this data is cleaned by banks and most of the features are masked for confidentaility. In Other word, This one is almost perfect data, where we dont need to worry much about the data wrangling and data manipulations.
