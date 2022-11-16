# (Dataset Exploration Title)
## by (your name here)


## Dataset

The dataset has 113937 observations of 81 variables. Data types including ‘float’, ‘int’, 'bool' and ‘object’. Most variables are numeric and categorical in nature. The dataset features can be split into two main categories:

1. Borrowers
2. Loan

## Summary of Findings

I wanted to explore the P2P lender’s data to find insights related to the borrowers and the loans they broker. At quick glance, there are about 113937 rows of loans and 81 variables. I initally choose way too many variables and through exploratory analysis, whittled it down to 20 variables and even created a few variables

In the univariate exploration, I visualized and addressed minor quality and tidiness issues for the following features:

Features for loan and borrower.

I. Borrowers

  1. Credit score 
  2. Debt to income ratio 
  3. Income 
  
II. Loans

  1. Loan amount 
  2. Interest rate
  3. Term
  
#### Numerical Features
Loan Amount
Debt to Income Ratio

#### Categorical Features
Income Range
Loan Status
Term

The bivariate exploration revealed that the debt coverage ratio and observed the higher the income, the lower the percentage of debt. The borrowers with high credit scores generally have lower interest rates and larger loan amounts. And this shows that as the lending platform matured, the overal risk exposure increased. Their main loan exposures are in debt consolidation and I’m sure the low interest rate environment has helped the supply of lenders looking for yield. This was a great learning experience about the P2P lending


## Key Insights for Presentation

For the presentation, I focus on the journey of exploring the influence of different variables such as the Original Loan Amount, Interest Rate, Income, Credit score and Term. I starter by introducing the above variable by plotting their distirbution .

Afterwards, I have used histogram, scatter plot, count plot, heatmap and box plot to dig deeper on the relationship between my variables.

## Requirements

1. Jupyter Notebook
2. Pandas
3. Numpy
4. matplotlib
5. seaborn

## Installation

To get the Jupyter Notebook running, execute the following in the command line and select Part_I_exploration_for_ProsperLoan.ipynb or to see the slide dec select Part_II_slide_deck_for_ProsperLoan.ipynb from the Jupyter Notebook dashboard.

$ git clone  git clone https://github.com/mzbekele/Prosper-Loan-Data-Analysis.git
$ cd Prosper-Loan-Data-Analysis
$ jupyter notebook

