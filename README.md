# Neural_Network_Charity_Analysis

## Analysis Overview
The purpose of this analysis is to create a binary classifier that is capable of predicting whether or not applicants will be successful if they are funded by Alphabet Soup.

## Results
The target for the model is the "IS_SUCCESSFUL" column which predicts whether or not the applicants will be successful if funding by Alphabet Soup.

The features for the model are the income amounts, application types, and special consideration columns.

The ID columns, "EIN" and "NAME" are neither targets nor features and should be removed from the input data.

In my initial model, I had 18 neurons among 2 layers, and 1 activation function. In order to improve the model, I increased the number of neurons, epochs, added a layer, and attempted to include more activation functions. Unfortunately, I wasn't quite able to achieve the 75% accuracy threshold, although I did get quite close. 

## Summary
Overall, the deep learning model does a decent job of predicting success rates of applicants if funded by Alphabet Soup with an accuracy of 72.6%. I would recommend using a 
support vector machine to solve the classification problem as they are similar to neural networks in the sense that they can analyze and interpret multiple data types. They are also great at classifing and creating regression using two groups which is all perfect for this dataset.
