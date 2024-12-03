# upGrad-Domain-Oriented-Case-Study


***upGrad - DS C67 - Course 3 - Case Study: "E-Commerce & Retail B2B"***


## Study Group

Nguyen Huu Liem - liemhuunguyen98@gmail.com

## Problem Statement
*Schuster is a multinational retail company dealing in sports goods and accessories.*


Schuster conducts significant business with hundreds of its vendors, with whom it has credit arrangements. Unfortunately, not all vendors respect credit terms and some of them tend to make payments late. Schuster levies heavy late payment fees, although this procedure is not beneficial to either party in a long-term business relationship. The company has some employees who keep chasing vendors to get the payment on time; this procedure nevertheless also results in non-value-added activities, loss of time and financial impact. Schuster would thus try to understand its customers’ payment behaviour and predict the likelihood of late payments against open invoices. 

 
To understand how to approach this problem using data science, let’s first understand the payment process at Schuster now. Every time a transaction of goods takes place with a vendor, the accounting team raises an invoice and shares it with the vendor. This invoice contains the details of the goods, the invoice value, the creation date and the payment due date based on the credit terms as per the contract. Business with these vendors occurs quite frequently. Hence, there are always multiple invoices associated with each vendor at any given time.

## Goal of the Case Study

- Schuster would like to better understand the customers’ payment behaviour based on their past payment patterns (customer segmentation).
- Using historical information, it wants to be able to predict the likelihood of delayed payment against open invoices from its customers.
- It wants to use this information so that collectors can prioritise their work in following up with customers beforehand to get the payments on time.

**To summarise, as a business analyst, you want to find the answer to these questions:**

- How can we analyse the customer transactions data to find different payment behaviours?
- In which way can you segregate the customers based on their previous payment patterns/behaviours?
- Based on the historical data, can you predict the likelihood of delayed payment against open invoices from the customers?
- Can you draw any business insights based on your developed model?

 
***Overall, you need to build a model with the primary objective of identifying important predictor attributes that will help the business understand indicators of late payment. You have to recommend the classification model that you would finally deploy for production and explain why you recommend it.***

## Data
You will primarily be looking at 2 specific tables - Past transactions record and open invoices. 

- Past transactions data contains the information of all the transactions that have been performed with various vendors in the past.
- Open invoices essentially contains the information of all the invoices that are open, *i.e. that haven't been paid yet.*
>Notes! 
- Your **target variable** will be whether the payment against an invoice was made on time or late.
- You have to use this dataset in a **70:30 ratio** to train and test your model.


## Results Expected
There are quite a few goals for this case study:

1. You have to conduct appropriate exploratory data analysis to extract useful insights (whether directly useful for business or for eventual modeling/feature engineering).
2. Once you performed the EDA, you can segregate the customer into different groups based on their payment pattern using historical data.
3. Next, you have to build a classification model. Make sure that your model output predicts whether a payment will be delayed or not at the invoice level. Note that, this is a classic binary classification problem.
4. After identifying important predictors, and the final model to be adopted by Schuster, you have to apply the model on the open invoice data to suggest how this model will be applied in real-time data going forward. You have to ensure that the probability of late payment is aggregated at a customer level.
5. You have to display your model’s outputs, that is, the customer segmentation output, visually – you can use plots, summary tables, etc. for this. Use whatever you think best conveys the importance of the features and the model’s results.
6. Finally, you have to identify customers for whom Schuster has to take precautionary measures beforehand.

## Output files
1. A well-commented Jupyter notebook includes detailed comments and should not contain unnecessary pieces of code.
2. The overall approach of the analysis in a PDF presentation:
    - Mention the problem statement and the analysis approach briefly 
    - Explain the results in business terms
    - Include visualisations and summarise the most important results in the presentation

## Referals
More details on the [Evaluation Rubric](https://learn.upgrad.com/course/5705/segment/56471/337370/1020282/5102073)

More details on the [LJMU's Masters In Data Science Program](https://www.upgrad.com/vn/masters-data-science-liverpool-john-moores-university-ljmu/)