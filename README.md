# House Price Prediction
### Advanced Regression Assignment
------------------------------------------
> In this case study, we used Advanced Regression techniques like Ridge and Lasso to come up with optimal predictions for Housing prices in Australian market.

-------------------------------------------
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->
-------------------------------------

## General Information

### Assignment Part I

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file:
> train.csv.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

- Which variables are significant in predicting the price of a house?
- How well those variables describe the price of a house.
- Determine the optimal value of lambda for ridge and lasso regression.

#### N.B. - 
You will find the complete analysis on the dataset in file:
> house_price_prediction.ipynb.

### Assignment Part II

Question 1
What is the optimal value of alpha for ridge and lasso regression? What will be the changes in the model if you choose double the value of alpha for both ridge and lasso? What will be the most important predictor variables after the change is implemented?

Question 2
You have determined the optimal value of lambda for ridge and lasso regression during the assignment. Now, which one will you choose to apply and why?

Question 3
After building the model, you realised that the five most important predictor variables in the lasso model are not available in the incoming data. You will now have to create another model excluding the five most important predictor variables. Which are the five most important predictor variables now?

Question 4
How can you make sure that a model is robust and generalisable? What are the implications of the same for the accuracy of the model and why?

Answers are in the pdf document named:
> Assignment_Part_II.pdf

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
---------------------------------------------------

## Conclusions

#### From this assignment I came to the following conclusion:

- The optimum lambda value in case of Ridge and Lasso is as follows: -
  - Ridge – 2 
  - Lasso – 0.0001
    
- The five most important predictor variables in the current lasso model is:-
  1. Total_sqr_footage 
  2. GarageArea 
  3. TotRmsAbvGrd 
  4. OverallCond 
  5. LotArea 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
-------------------------------------------

## Technologies Used

- Jupyter Notebook
- Python
- Modules - Seaborn, Matplotlib, Pandas, Numpy, SciKit Learn, StatsModels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
-------------------------------------------------

## Acknowledgements
- Truly thankful to the instructors and my colleagues who have provided constant help and support whenever necessary.

---------------------------------------------------

## Contact
Project by Prashant [@prixroxx](https://www.github.com/prixroxx) - feel free to contact me for any questions or clarifications!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
