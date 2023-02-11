# Banknote_Verification_Project-
Purpose
We are creating a way of verifying whether a banknote is original(genuine) or forged(fake). We are using K-Means algorithm to train our model to perform this very action. 
Description of the Data
We have provided a data set containing 1,372 banknotes some which are genuine and some which are false. 
Methods: how the data was analyzed
We used the data set provided to train our model using K-Means algorithm. This is just to ensure that our model will be able to tell the two types of banknotes apart.
K-Means is a type of algorithm used in the case of unsupervised learning grouping unlabeled data set into different clusters. Each cluster will be such that a dataset will belong to only one group with which it shares similar characteristics. The K is used to define the number of clusters created as in our case we grouped them into two clusters(K=2)
We imported the necessary libraries that would assist us in performing the required operations on the data e.g. putting our data into a table format, visualizing our data etc.
We pulled out the 2 columns we were interested in (v1 & v2) from the data set we were provided with. Afterwards applied K-Means algorithm to the 2 columns (we had conflated into one column first) and came up with the 2 clusters we had pre-defined.
We ran K-Means multiple times (9) to see if our clustering was stable
