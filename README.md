# Predicting Consumer Loan Defaults in India
Prepared by Rahul D. Raju

# Abstract
Over the past 20 years the economy of India has experienced unprecedented growth, increasing at an average annual rate of 6.50%.  
This has been largely led  by the  information technology boom that has created a shift in demography, an affluent middle class and growth in rural economies. 
Millennials and Gen-Z now have access to better education and employment opportunities, resulting in rising incomes and growing consumption habits.  
This in turn has led to a consumer credit boom with growth in credit averaging 15.00% per year over the past 2 decades.  WIth this rise in credit comes 
great opportunity as well as great risk, particularly as the evolution in technology leads to greater financial inclusion in lower socio-economic classes. 
As such, India will need enhanced risk management techniques to ensure the continued grow of credit and well as the overall stability of its financial 
system. ImpactHistorically, legacy banks provided personal loans based on close business relationships as well as high value collateral. 
This lent itself to a very archaic and crude credit approval process.  Recently, technological innovation in the finance industry has led to many smaller 
institutions offering unsecured loans.  Data science methodologies could benefit both legacy and new firms alike in providing a more scientific approach
to the credit approval process.  This would allow for improved risk management, greater financial stability and more extensive access to credit markets 
across all socio-economic classes.  SolutionA classification model could provide for the ability to better predict consumer loan defaults based on 
sound statistical techniques.  

# Data
The data set used in this analysis was found on Kaggle and is maintained by the University of Alabama.  
Below are the major characteristics of the data set:  
Number of Observations:  252,000                
- Loan Defaults(Positives):  30,996      
- No Loan Defaults(Negative):  221,004
Number of Columns:  13
Number of features:  11    
- Quantitative:  5    
- Categorical:  6

# Methodology and Algorithms
1.  Data Acquisiton
2.  Data Cleaning
3.  Exploratory Data Analysis
4.  Pre-processing data
5.  Evaluation Metric Choice
6.  GridSearch CV across multiple algorithms including Knn, Decision Trees, Logistic Regression, Random Forest, XGBoost


# Tools
1.  Exploratory Data Analysis:  
       - Data Cleaning and manipulation:  Pandas, Numpy
       - Data Visualization:  Matplotlib, Seaborn
2.  Statistical Analysis:  Sci-Kit Learn 


# Results Summary
Random Forest proved to be our best performing model, optimizing for F-Beta:

Accuracy: 0.8956944444444445
Precision: 0.5581775700934579
Recall: 0.7641132256516872
F1 Score: 0.6451090258556673
f2_score: 0.7369249039900057
roc_auc_score: 0.9381846137370948
log_loss: 0.2504906321721783





