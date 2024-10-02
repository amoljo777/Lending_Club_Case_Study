This is a case study on Lending Club data analysis, done as part of an EDA assignment for  PG Programme in Machine Learning & AI - July 2024 

Lending-Club-Case-Study
===========================

PROBLEM STATEMENT
-------------------

INTRODUCTION

Solving this assignment will give you an idea about how real business problems are solved using EDA. In this case study, apart from applying the techniques you have learnt in EDA, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.
  

BUSINESS UNDERSTANDING

You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.


In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

https://cdn.upgrad.com/UpGrad/temp/7afbce98-8ecc-41c6-96d8-981cba7d343f/Loan_image.png

Figure 1. Loan Data Set

When a person applies for a loan, there are two types of decisions that could be taken by the company:

1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
Business Objectives
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

DATA UNDERSTANDING

Download the dataset from below. It contains the complete loan data for all loans issued through the time period 2007 t0 2011.

https://cdn.upgrad.com/UpGrad/temp/3ba74fb7-bd88-4854-8597-1c225a5aed99/loan.zip

You can access the data dictionary which describes the meaning of these variables from the provided link below:

https://cdn.upgrad.com/UpGrad/temp/af860da6-f838-47d6-ad97-551022550ee4/Data_Dictionary.xlsx

RESULTS EXPECTED

Write all your code in one well-commented Python file; briefly mention the insights and observations from the analysis

Present the overall approach of the analysis in a presentation

 Mention the problem statement and the analysis approach briefly 

 Explain the results of univariate, bivariate analysis etc. in business terms

 Include visualisations and summarise the most important results in the presentation
 
You need to submit one Ipython notebook which clearly explains the thought process behind your analysis (either in comments of markdown text), code and relevant plots.

Important Note: Please make sure to rename your Python notebook "Group_Facilitator_Name.ipynb".

---------------------------------------------------------------------------------------------------------------------------

Introduction -
Data analysis of this case study categriesed in following steps-

Data cleanning
Univariate Analysis
Bivariate/Multivariate Analysis
Result
Method Used
Exploratory Data Analysis(EDA)
Data Visualization
Technology Used
Python
Pandas
Juipter
NumPy
Metplotlib
missingno
seaborn etc.
Conclusions/Suggestions
Lending club shuold consider to accepting more loans request less then 10% interest rate as their probabity of charged_off is have lesser.

Lending club shuold consider to accepting more loans request for borrowers which owning house their have lees probabilty to Charged_off.

Lending club shuold consider to accepting more loans request for grade A respect to B C D becuase in B C D E have lots off Charged_off

Lending club shuold consider to accepting more loans request of borrowers which have annual income gretaer then 90000 its charged_off % have nearest 10%.

Lending club need to accept more loan for 36 month term there have less chances of charged_off and it continuously increasing year by year.

Lending club need to accept loan which owning house, annual income have greater then 90000, interest rate is less then 10%.This combination is have less chances to charged_off.

Lending club should accept more loan request of borrowers which one have source verified or verified. Their have less chance of charged_off.

Lending club should accept more loan request of borrowers which one have employment experienc less then 10 years.

Lending club should accept more loan for applied for wedding, major_purchase, car and credit_card here have chances of charged_off is less nearest 10% but for small business have 27.97% charged_off.

Lenading club should accept the loan request for small loan amount For loan amount till 14K charged_off(nearest 13%) have low risk

Lenading club should accept the loan request for coming from addres state IN IA and ME here having low risk of charged off.

Contributer

CONTRIBUTOR
Amol Joshi
