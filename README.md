# Customer-segmentation
## Problem Statement
Develop a customer segmentation to define marketing strategy
## Goal of Model
* Advanced data preparation: Build an ‘enriched’ customer profile by deriving “intelligent” KPIs.
* Advanced reporting: Use the derived KPIs to gain insight on the customer profiles. 
* Identification of the relationships/ affinities between services. 
* Clustering: Apply a data reduction technique factor analysis for variable reduction technique and a clustering algorithm to reveal the behavioural segments of credit card holders 
* Identify cluster characterisitics of the cluster using detailed profiling. 
* Provide the strategic insights and implementation of strategies for given set of cluster characteristics

## Data Description
  * CUST_ID: Credit card holder ID
	* BALANCE: Monthly average balance (based on daily balance averages)
	* BALANCE_FREQUENCY: Ratio of last 12 months with balance
	* PURCHASES: Total purchase amount spent during last 12 months
	* ONEOFF_PURCHASES: Total amount of one-off purchases
	* INSTALLMENTS_PURCHASES: Total amount of installment purchases
	* CASH_ADVANCE: Total cash-advance amount
	* PURCHASES_ FREQUENCY: Frequency of purchases (Percent of months with at least one purchase)
	* ONEOFF_PURCHASES_FREQUENCY: Frequency of one-off-purchases PURCHASES_INSTALLMENTS_FREQUENCY: Frequency of installment purchases
	* CASH_ADVANCE_ FREQUENCY: Cash-Advance frequency
	* AVERAGE_PURCHASE_TRX: Average amount per purchase transaction
	* CASH_ADVANCE_TRX: Average amount per cash-advance transaction
	* PURCHASES_TRX: Average amount per purchase transaction
	* CREDIT_LIMIT: Credit limit
	* PAYMENTS: Total payments (due amount paid by the customer to decrease their statement balance) in the period
	* MINIMUM_PAYMENTS: Total minimum payments due in the period.
	* PRC_FULL_PAYMEN: Percentage of months with full payment of the due statement balance
	* TENURE: Number of months as a customer
  
  ## Conclusion
  ### Insights with 4 Clusters
* Cluster 0 is the group of customers who have highest PURCHASES_FREQUENCY. This group is about 45% of the total customer base
* Cluster 2 have high installments purchases and purchase frequency. This group is about 30% of the total customer base
* Cluster 1 customers have highest balance and credit limit. This group is about  20% of the total customer base
* Cluster 3 customers have paid their due amount and they use credit card more often. This group is about 10% of the total customer base.

### Strategy Suggested
* Group 1
Bulk of the customers. Try for them to use the card more frequently. Give reward programs to them.
* Group 2
These are VIP clients, find ways for them to buy more. 
* Group 3
These customers use the credit card for installment purchases. They are financially wise.
* Group 4
Very profitable customers. They use the card most often.



  
  
