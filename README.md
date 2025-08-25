## Project Background:

The project is centered around the supply-chain industry, where the company is facing financial losses due to excess payouts to delivery partners. 

The task is to identify bottlenecks and develop a standard dynamic calculator to determine the commercials for each partner, thereby optimizing the overall profit of the organization and its partners, which addresses the concerns of both the operations and finance teams.

Insights and recommendations are provided on the following key areas:

- **Overpayment Analysis:** Analysis of payment data to verify claims of overpayment and identify the underlying reasons. 
- **Cost Structure:** Provides details of each partner's expenses related to their fleet of vehicles.
- **Profitability Analysis**: Comparison of partners' expenses and payouts to understand profitability.
- **Cost Calculator**: A standardized model for calculating partners' cost and payouts. 

An interactive dashboard for overpayment analysis: 

Cost structure of delivery partners:

Partner Profitability Analysis:

Cost Calculator:

## Data Structure:

The company’s database structure as seen below consists of 4 tables: payout, business_partners, branch and vehicles.
<img width="1920" height="1080" alt="last_mile_ERD" src="https://github.com/user-attachments/assets/ea343e43-672c-4376-9c7a-abddadd61a94" />


## Executive Summary:

A huge amount has been overpaid to the partners which is about 15 millions, 31% larger than the expected budget. 
The Ahmedabad cluster has been identified as overpaid by a significant margin of 2.3 million, which is approximately double the budgeted amount. 
Applying Pareto's principle, digging into the cause of overpayment in Ahmedabad cluster will help identify the key areas of improvement. 

<img width="1174" height="340" alt="last_mile_executive_summary" src="https://github.com/user-attachments/assets/abd337b6-0834-46c3-bc5b-658df61d61a4" />

The entire interactive dashboard can be explored here: https://www.novypro.com/project/overpay-analysis


## Insights:

## Recommendations:

### **Overpayment Analysis:**

A dashboard is prepared to compare actual payouts and budgets which aims to determine the number of clusters where payouts exceeded the budget, identify the cluster where the problem is most severe, and provide insights into the number of branches within that cluster that either experienced overpayments or fell below the budget allocation.

*Findings* - The Ahmedabad cluster has been identified as overpaid by a significant margin of 2.3 million, an amount equivalent to the budgeted payout. Let’s apply the Pareto principle here and dig in further to find the cause of overpayment in the Ahmedabad cluster. 

**Live Dashboard:** https://www.novypro.com/project/overpay-analysis

### **Building Cost Structure:**

A cost structure is prepared to validate the cost of partners and find out the possible causes of high variance between target and actuals. This model will help to calculate the cost of every vehicle of a partner, thereby determining the cost per kg.

### **Profitability analysis:** 

Now, we have a cost structure to calculate each partner’s cost, and the commercials and loads delivered by each partner of Ahmedabad are also provided. Now,  profitability analysis is performed which will help us understand whether the finance team kept the budget too low or partners’ payout rates were set too high, or both.

The correlation value of cost per kg and payout per kg is very low, the whole cost model is disrupted. Most of the partners are at a loss even after the payout is higher than the budget for each partner.

### **Improving cost structure:**
The cost structure prepared shows inflated costs. So, some improvements are made like correcting EMI costs, substituting fuel cost of market vehicles as 0, correcting market vehicle cost, checking the number of loaders and drivers, etc.
Now, the number of partners who have gained profit has slightly increased.

To increase the profit, we have to increase the per kg rate offered. The per kg rate will depend on the cost per kg and the cost per kg will come from fuel cost per liter, distance travelled, etc. The more vehicles the partner will have, the more cost per kg will increase.

So, a partner having more vehicles should deliver more kgs. To verify that, utilization % is calculated and it is observed that the vehicle utilization is very low, hence decreasing profit margin.
So, a new cost calculator should be designed to calculate the payout per kg of a partner by maximizing vehicle utilization.

### **Commercials Calculator:** 
So, to solve the problem, a calculator is created that calculates the standardized cost per kg of a partner at 80% of utilization and outputs a payout rate that can be offered to them.

The profit margin of the partner can be adjusted and based on that the payout is calculated.

This calculator will standardize payouts and help the finance team plan and allocate the budget accordingly, making payouts fair to the partners.
