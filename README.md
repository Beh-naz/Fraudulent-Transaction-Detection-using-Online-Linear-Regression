# Fraudulent Transaction Detection using Online Linear Regression

## Project Overview
This project focuses on the implementation of an online linear regression model to predict fraudulent transactions using financial data. The goal is to compare the efficiencies of online versus offline learning models, particularly in terms of memory and time utilization. Online learning has been chosen for its ability to update models incrementally, avoiding the overheads of data storage and model re-computation.

## Data
The data used in this project consists of transaction details, including the types and amounts of transactions, balances, and a flag indicating whether the transaction is fraudulent. 

## Prerequisites
To run the scripts, you will need R and the following R packages installed:
- `caret`
- `ggplot2`


You can install these packages using the following commands in your R console:

install.packages("caret")


install.packages("ggplot2")

## Results
The implemented online linear regression model achieved an accuracy of 85% in detecting fraudulent transactions.

## Further Work
Plans to extend this project include testing two additional methods on the dataset and benchmarking their performance in terms of efficiency.

## Collaborators
This project was carried out in collaboration with a colleague, Xiao Lian, with a shared interest in financial data analysis.


