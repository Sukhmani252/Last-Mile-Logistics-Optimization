## Project Overview:

The project is centered around the supply-chain industry, where the company is facing financial losses due to excess payouts to delivery partners. 

The task is to identify bottlenecks and develop a standard dynamic calculator to determine the commercials for each partner, thereby optimizing the overall profit of the organization and its partners, which addresses the concerns of both the operations and finance teams.

Insights and recommendations are provided on the following key areas:

- **Overpayment Analysis:** Analysis of payment data to verify claims of overpayment and identify the underlying reasons. 
- **Cost Structure:** Provides details of each partner's expenses related to their fleet of vehicles.
- **Profitability Analysis**: Comparison of partners' expenses and payouts to understand profitability.
- **Cost Calculator**: A standardized model for calculating partners' cost and payouts. 

An interactive dashboard for overpayment analysis can be downloaded [here](https://github.com/Sukhmani252/Last-Mile-Logistics-Optimization/blob/main/overpay_analysis.pbix) 

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



### Insights and Recommendations:

- **Overpayment Issue:** Analyzing the budget and payouts resulted in Ahmedabad being the most overpaid cluster. Breaking down the partner cost structure of Ahmedabad can help uncover system-wide inefficiencies.
  
- **Cost Structure:** A cost structure is built to determine the cost incurred for the vehicles by partners, which depends on the vehicle's capacity, mileage, ownership type, and distance travelled, and mainly includes fuel cost, EMI, maintenance, vehicle cost, and team cost.

- **Profitability Analysis:** Comparing costs and payouts showed that only 35% of Ahmedabad partners are profitable, while the majority are operating at a loss.

- **Cost vs Payout:** The correlation between cost per kg and payout per kg is very low. Costs are significantly higher than payouts, leading to losses despite partners being overpaid. It indicates that the partners are not being paid correctly, the whole cost structure is disrupted, and there is a need to develop a new standardized commercials calculator for determining partners’ costs and payouts.

- **Utilization:** To understand the cause behind high costs, vehicle utilization is measured against monthly capacity vs actual kg delivered, which comes out to be very low. 

   The utilization is thus directly correlated with the profit margin – the higher the utilization, maximum the profits.
  

 <img width="917" height="365" alt="Utilization vs Profit Margin" src="https://github.com/user-attachments/assets/a815744b-a135-4ba4-91f5-7c1212f6f3c0" />

### Solution – Commercials Calculator:

-   A calculator is designed to take partner vehicle information as input, which computes costs such as fuel, maintenance, vehicle, manpower, and additional charges.
   
- The standardized cost calculator determines overall costs and outputs a payout rate for partners based on their vehicle type, assuming 80% vehicle utilization. The partner’s profit margin can also be adjusted to ensure fair payouts.

<img width="1588" height="1000" alt="Cost Calculator" src="https://github.com/user-attachments/assets/d1563bdc-ab58-44dc-b8b9-1a8e136f53b0" />






