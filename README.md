\# 📊 Marketing ROI, Customer Segmentation \& Cohort Analysis (Excel)



<p align="center">

<img width="920" height="400" alt="dashboard\_image" src="https://github.com/user-attachments/assets/c334c1b7-325b-4bd9-832e-f289a9d07b8c" />

</p>



\## Executive Summary



This project analyzes marketing investments to evaluate how effectively they drive revenue across channels and customer segments. The analysis reveals diminishing returns as marketing spend increases, with significant variation in ROI across channels. A small group of high-value customers contributes a disproportionate share of revenue, highlighting strong opportunities for targeted retention strategies.



Cohort analysis further shows that newer customer cohorts are more active but have lower lifetime spend so far, while older cohorts generated higher value but exhibit declining engagement. These insights support clear, data-driven actions: rebalance marketing budgets toward high-ROI channels, focus on high-value customers, and implement lifecycle-based engagement strategies.



---



\## 💼 Business Impact



\- Identified Store channel as highest ROI (19×), supporting budget reallocation

\- Revealed over-investment in Web marketing (45% spend, only 27% revenue)

\- Showed top 20% of customers drive 52% of revenue → retention priority

\- Highlighted churn risk in older cohorts → reactivation opportunity



---



\## 🎯 Project Objectives



\* \*\*ROI Analysis:\*\*

  Quantify overall marketing ROI and analyze how ROI changes under different budget scenarios (low, base, high spend).



\* \*\*Channel Performance:\*\*

  Attribute revenue to marketing channels and evaluate ROI to identify top- and under-performing channels.



\* \*\*Customer Segmentation:\*\*

  Segment customers into High, Mid, and Low value tiers based on total spend percentiles.



\* \*\*Cohort Analysis:\*\*

  Analyze monthly customer cohorts by join date to assess cumulative value, engagement, and churn risk.



---



\## 🗂️ Data Overview



\* \*\*Customers:\*\* 2,214 retail customers

\* \*\*Time Period:\*\* August 2012 – June 2014

\* \*\*Total Revenue:\*\* $1.34M

\* \*\*Marketing Channels:\*\* Web, Store, Catalog, Deals



Each customer’s revenue was attributed proportionally to channels based on purchase behavior (e.g., if 50% of purchases were online, 50% of revenue was attributed to Web).



\### Key Data Features



\* Spend by product category (e.g., `MntWines`, `MntFruits`)

\* Purchases by channel

\* Recency (days since last purchase)

\* Campaign response and acceptance metrics

\* Engineered fields for ROI, segmentation, and cohort analysis



---



\## 🧮 Methodology \& Metrics





Detailed formulas are documented separately.



📄 \*\*Methodology \& Formula Reference (PDF):\*\*  \[View detailed formulas](https://github.com/javed-analytics/Marketing-ROI-Customer-Segmentation-Cohort-Analysis/blob/master/scripts/Excel%20Formulas.pdf)





\### Marketing ROI





ROI = (Revenue − Spend) / Spend





\* \*\*Baseline Budget:\*\* $103K (7.7% of revenue)

\* \*\*Low Budget:\*\* −20% of baseline

\* \*\*High Budget:\*\* +20% of baseline



Revenue was held constant to analyze ROI sensitivity.



\### Channel Budget Allocation



\* Web: 45%

\* Store: 25%

\* Catalog: 20%

\* Deals: 10%



ROI was calculated using attributed revenue per channel.



---



\### Customer Segmentation



Customers were segmented by total lifetime spend (`MntTotal`):



| Segment    | Percentile | Spend Range   |

| ---------- | ---------- | ------------- |

| High Value | Top 20%    | $1,175+       |

| Mid Value  | 50–80%     | $400 – $1,175 |

| Low Value  | Bottom 50% | < $400        |



---



\### Cohort Analysis



Customers were grouped by \*\*join month\*\* (first purchase).



\*\*Key Metrics\*\*



\* New Customers

\* Cohort Revenue

\* Avg. Revenue per Customer

\* Value Index (vs. overall average)

\* Active Rate (purchase in last 30 days)

\* At-Risk Rate (no purchase in 90+ days)



Additional engagement metrics included channel mix, web visits, campaign response, acceptance, and complaints.



---



\## 📈 Key Findings



\### ROI \& Budget Sensitivity



\* \*\*Low Budget ROI:\*\* ~15.2×

\* \*\*Base Budget ROI:\*\* ~12.0×

\* \*\*High Budget ROI:\*\* ~9.8×



Increasing spend beyond ~7.7% of revenue produced diminishing returns. The optimal budget range is near the current baseline.



<table>

&nbsp; <tr>

&nbsp;   <td>

&nbsp;     <img width="1109" height="800" alt="overall-roi-budget-sensitivity" src="https://github.com/user-attachments/assets/698afca4-e7cc-4789-bb00-cbbd063d3059" />

&nbsp;   </td>

&nbsp;   <td>

&nbsp;     <img width="1536" height="990" alt="Picture1" src="https://github.com/user-attachments/assets/c9ec2a19-78c5-44eb-8fe5-4ca209c05adc" />

&nbsp;   </td>

&nbsp; </tr>

</table>



---



\### Channel Performance



\* \*\*Store:\*\* Highest ROI (~19×), 39% of revenue on 25% of spend

\* \*\*Catalog \& Deals:\*\* Strong ROI (~13–14×)

\* \*\*Web:\*\* Lowest ROI (~6.7×), 45% of spend but only 27% of revenue



👉 Indicates over-investment in Web and under-investment in Store.



<table>

&nbsp; <tr>

&nbsp;   <td>

&nbsp;   <img width="1103" height="974" alt="channel-revenue-pie" src="https://github.com/user-attachments/assets/374ca904-fa70-4c3a-b4f2-72f80cc95e60" />

&nbsp;   </td>

&nbsp;   <td>

&nbsp;    <img width="1420" height="990" alt="channel-roi-revenue" src="https://github.com/user-attachments/assets/7ad0e6cd-6e4c-46b5-b4c2-31e5a893a92f" />

&nbsp;   </td>

&nbsp; </tr>

</table>



---



\### Customer Segmentation Insights



\* \*\*High-Value Customers (20%) → 52% of revenue\*\*

\* \*\*Mid-Value Customers (30%) → 39% of revenue\*\*

\* \*\*Low-Value Customers (50%) → 9% of revenue\*\*



Average High-Value customer spend (~$1,586) is:



\* 2× overall average

\* 14× Low-Value customer spend



<table>

&nbsp; <tr>

&nbsp;   <td>

&nbsp;     <img width="992" height="1682" alt="Picture3" src="https://github.com/user-attachments/assets/424705b7-1f4d-4b7d-8b76-fd7ef24a7440" />

&nbsp;   </td>

&nbsp;   <td>

&nbsp;     <img width="2179" height="1013" alt="Picture1" src="https://github.com/user-attachments/assets/62dbd0a4-9fc3-404c-b105-c926f900d128" />

&nbsp;   </td>

&nbsp; </tr>

</table>



---



\### Cohort Analysis Insights



Older cohorts (2012–2013):



\*  Higher lifetime value 

\*  Lower engagement (25–30% active) 

\*  Higher churn risk 



Newer cohorts (2014):



\*  Lower spend so far 

\*  Higher activity (35–40% active) 

\*  Low churn risk 





As cohorts age, \*\*value increases but engagement declines\*\*, highlighting the importance of retention strategies.



<table>

&nbsp; <tr>

&nbsp;   <td>

&nbsp;    <img width="1637" height="990" alt="Picture6" src="https://github.com/user-attachments/assets/8c8f27ea-c9a8-4692-8f64-9eaacb919412" />

&nbsp;   </td>

&nbsp;   <td>

&nbsp;    <img width="1571" height="990" alt="Picture7" src="https://github.com/user-attachments/assets/28565aa3-6219-4b5a-ac6b-558f4c63f112" />

&nbsp;   </td>

&nbsp; </tr>

</table>



---



\### Digital Engagement \& Campaign Response



\* Web visits remain high across cohorts

\* Campaign response rates decline over time

\* Acceptance rates remain moderate

\* Complaint rates remain consistently low



📌 Indicates opportunity for better personalization rather than customer dissatisfaction.



<img width="1473" height="971" alt="Picture5" src="https://github.com/user-attachments/assets/17d0d1aa-0359-40fb-8757-af1ea71b1c67" />



---



\## 💡 Business Recommendations



\### 1. Reallocate Budget to High-ROI Channels



Reduce Web spend and increase Store and Catalog investment.



\### 2. Optimize Web Marketing



Improve targeting, creatives, and conversion funnels. Limit spend to proven campaigns.



\### 3. Focus on High-Value Customers



Introduce loyalty programs, VIP offers, and premium experiences.



\### 4. Grow the Mid-Value Segment



Use upselling, personalized recommendations, and engagement campaigns.



\### 5. Retention \& Reactivation



Launch win-back campaigns for at-risk customers and strengthen onboarding for new customers.



\### 6. Right-Size Marketing Budget



Avoid overspending; test increases incrementally with ROI tracking.



\### 7. Continuous Monitoring



Track ROI, segments, and cohorts regularly and validate insights through A/B testing.



---



\## ⚠️ Limitations



\* Simplified channel attribution (no multi-touch model)

\* Revenue assumed static in budget sensitivity analysis

\* No transaction-level dates

\* Limited cohort lifespan (data through 2014)

\* Segmentation based only on spend

\* Results dependent on data accuracy and context



---



\## 🚀 Next Steps



\* Rebuild analysis using \*\*SQL\*\* for scalability

\* Create automated dashboards in \*\*Power BI\*\*

\* Extend cohort tracking with newer data



---

