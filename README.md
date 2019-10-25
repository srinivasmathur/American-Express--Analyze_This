# American-Express--Analyze_This
'Analyze This' is a Data science contest organized by American Express across IITs to hire students. 

# Problem Statement -To predict and segment the credit line of the customer into low,medium and high based on credit card data,income,revenue etc.

The following features were provided:

Variable Name	Definition
VAR1-	ID	The identifier for the account
VAR2-	FICO	Credit score associated with account. Takes into account: payment history, current level of indebtedness, types of credit used, length of credit history, and new credit accounts. Higher is better.
VAR3-	Business Revenue	Reported annual business revenue
VAR4-	TSR	Risk score associated with probability of default (internal with company or external with any other firm). Lower score means lower risk.
VAR5-	Last 6M Avg Util	Average utilization of credit line in the last six months (Balance/credit line)
VAR6-	Income	Reported annual business income
VAR7-	Last 6M Avg Remit	Average amount paid towards card bills in the last 6 months
VAR8-	Last 6M Avg Bal	Average balance on each card in the last 6 months
VAR9-	Internal Revolve	The average daily balance as a percentage of cycle cut balance with XYZEE (all accounts)
VAR10-	Lending AR% in last 6M	Percentage of internal balance (with XYZEE) on the lending card (of lending and charge card total)
VAR11-	ExternalBalance	Total balance on external cards\n
VAR12-	Months in Business	Total number of months the entity has been in business
VAR13-	preferred_spend_line	The credit line on external card with maximum spending
VAR14-	total_cards	Number of accounts with XYZEE associated with the same entity
VAR15-	preferred_bal_line	The credit line on external card with maximum balance
VAR16-	preavgremit1_3_all	Average amount paid towards card bills in the last 3 months
VAR17-	External_rev_rate	The average daily balance as a percentage of cycle cut balance on all external accounts
VAR18-	Supplementary Cards	Number of supplementary cards issued on the same account. It is the privilege offered to a relative/associate of the primary card holder to use the same account. The balance incurred on the supplementary card is added to the main account.
VAR19-	isChargeCust	Indicator saying whether the customer also has a charge card account
VAR20-	CMV	This is the lifetime value associated with each account
VAR21-	Assigned Line	This is the segment of credit line provided to each account
	
## Scoring- A custom scoring model was to be made as instructed in the contest to measure the performance of the model. 
