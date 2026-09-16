# RFM-Analysis
Performed RFM analysis to segment customers based on recency, purchase frequency, and monetary value. Identified high-value customers at risk of churn and developed targeted retention, win-back, and customer growth strategies. Two high-value at-risk customers accounted for 42% of total business revenue.

https://docs.google.com/spreadsheets/d/1UWUQaISSq5lFTOkb8UzVdryrnzh149yYe6ZbztHljNY/edit?gid=1169551708#gid=1169551708

| **Customer_ID** | **Last_Purchase_ Days_Ago** | **Purchases** | **Total_Spend** | **R** | **F** | **M** | **RFM** | **Customer_segment** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C001 | 5 | 12 | $1,500 | 5 | 5 | 4 | 554 | Champions |
| C002 | 20 | 8 | $900 | 3 | 3 | 3 | 333 | Loyal Customers |
| C003 | 120 | 10 | $1,800 | 2 | 4 | 4 | 244 | At Risk High Value |
| C004 | 250 | 2 | $100 | 1 | 2 | 1 | 121 | Lost Customers |
| C005 | 10 | 1 | $50 | 4 | 1 | 1 | 411 | New Customers |
| C006 | 45 | 6 | $700 | 2 | 3 | 3 | 233 | Other |
| C007 | 8 | 15 | $2,000 | 4 | 5 | 5 | 455 | Champions |
| C008 | 180 | 12 | $2,200 | 1 | 5 | 5 | 155 | At Risk High Value |
| C009 | 30 | 3 | $250 | 3 | 2 | 2 | 322 | Other |
| C010 | 3 | 2 | $150 | 5 | 2 | 2 | 522 | New Customers |

### Questions

**1.** Which customer has the highest monetary value?
- Customer C008 has the highest monetary value with a total spend of $2200

**2.** Which customer has the highest purchase frequency?
- Customers C007, C001, and C008 have the highest purchase frequency, with 15 for C007 and 12 purchases each  for C001 and C008

**3.** Which customers are potentially at risk based on recency?
-  Customers C003, C004, and C008 are potentially at risk based on recency

**4.** Which customer would concern you most: C004, C003, or C008? Explain why.

| Customer_ID | % Contribution to Overall B/s Revenue  |
| --- | --- |
| C008 | 23% |
| C003 | 19% |
| C004 | 1% |
- Customers C008 and C003 would concern me the most since they contribute to 23% and 19% respectively of the overall business revenue, and they haven’t made purchases in last 90 days meaning they are high value customers at risk and losing them could heavily impact business revenue.

**5.** Which customers look like strong candidates for “Champions”?
- C001 and C007

**6.** Which customers appear to be new/low-frequency customers?
- C005 and C0010

**7.** Calculate the average spend per purchase for C001.

Use:

**Average spend per purchase = Total Spend ÷ Purchases
= $1500/12 = $125 per purchase** 

**8.** Why could C008 be more important to the business than C004 even though both are at risk?
- Customer C008 contributes 23% of the overall business revenue, making him a high-value customer at risk who has not purchased in the last 180 days, compared to C004, who contributes 1% of the overall b/s revenue. Losing customer C008 could heavily impact the total business revenue  

**9.** If overall churn increased, what customer segments would you investigate first?
- I would investigate high-value customers who have churned, since they have a heavy impact on overall business revenue. 

**10.** Give **three business actions** based on your analysis.
- 

**VIP Retention & Win-Back Strategy**

- **Re-engage High-Value "At Risk" Customers (C003 & C008):** Launch high-touch, personalized outreach (e.g., dedicated account management, exclusive executive perks, or tailored discounts) to re-activate C008 and C003. Together, they account for 42% of total revenue but haven't purchased in over 120–180 days.
- **Reward and Nurture Champions (C001 & C007):** Enroll these high-frequency, high-spend customers into an exclusive VIP loyalty program or invite them to give product feedback/early beta access. Keeping them engaged prevents churn among your highest-value segment.

**Customer Lifecycle Activation**

- **Onboard & Upsell New Customers (C005 & C010):** Set up automated post-purchase email onboarding sequences with product recommendations or time-limited follow-up offers. This encourages recent, low-frequency buyers to make their second purchase and transition into repeat customers.

**Segmentation & Targeted Marketing**

- **Tailor Campaigns by Segment:** Move away from generic marketing blasts by personalizing campaigns based on RFM scores:
    - **Lost Customers (C004):** Low-cost automated win-back emails or retargeting ads rather than expensive manual outreach.
    - **Loyal & Mid-Tier (C002, C006, C009):** Cross-sell complementary products to boost their purchase frequency and order values toward Champion status.
