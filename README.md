# Unsupervised-Learning
 1. Data is read from crypto_data.csv
 #drop IsTrading Column
#Remove all rows that have at least one null value.
#Remove all rows that have at least one null value.
#Filter for cryptocurrencies that have been mined. That is, the total coins mined should be greater than zero.
#delete the `CoinName` from the original dataframe
#delete the unnamed column(unnecessary)
#convert the remaining features with text values, `Algorithm` and `ProofType`, into numerical dat
#standardise the data
#Examine the number of rows and columns of your dataset
# Perform dimensionality reduction with PCA
#Initialize PCA model
#Get two principal components for the data.
#reduce the dataset dimensions with t-SNE
#Apply a fit-transform
#Cluster Analysis with k-Means
#Plot the Elbow Curve

it seems crypto currencies does not make any meaningful clusters and thats why can't recommend any model for this. Also 
this data not making any elbow shaped curve to recommend any meaningful k-numbers.
