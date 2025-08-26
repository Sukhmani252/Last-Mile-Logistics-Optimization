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

<img width="1174" height="327" alt="last_mile_executive_summary" src="https://github.com/user-attachments/assets/5227fdb3-1393-4c04-91e1-250cfdc937c8" />


The entire interactive dashboard can be explored here: https://www.novypro.com/project/overpay-analysis



#### Insights and Recommendations:

Overpayment Insight, recommendation/call to action - (understanding cost structure)

A cost structure is built to understand the cost incurred for the vehicles by partners which depends on the vehicle's capacity, mileage and distance travelled and mainly includes fuel cost, EMI, maintenance, vehicle cost and team cost.

 - percentage of profitable partners
Despite the partners being overpaid, most of them are at loss. Only 29% of all the partners are profitable.
 - correlation b/w cost per kg and payout per kg
 - more on profitability analysis - utilization

 <img width="917" height="365" alt="Utilization vs Profit Margin" src="https://github.com/user-attachments/assets/a815744b-a135-4ba4-91f5-7c1212f6f3c0" />

 - Raw Calculator Inputs
 - cost calculator
   
- A new cost calculator is created based on the vehicles of partner to calculate the standardized cost per kg by keeping vehicle utilization as 80% and outputs a payout rate that can be offered to partners.
The profit margin of the partner can also be adjusted and based on that the payout is calculated.



