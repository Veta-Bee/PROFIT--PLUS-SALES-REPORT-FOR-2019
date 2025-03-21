  # PROFIT--PLUS-SALES-REPORT-FOR-2019

![PROFIT -PLUS DASHBOARD](https://github.com/user-attachments/assets/ab663f9b-3f50-41a1-8538-d7b65255b675)

**INTRODUCTION**

The "Profit-Plus Sales Analysis Report for 2019" presents a detailed overview of the company's total sales of $322,966.75, highlighting Branch C as the best-performing branch, January 2023 as the month with the highest sales, Food & Beverage as the top product line, cash as the most used payment method, and members as the best customer type, while breaking down sales by gender—male ($167,882.93) and female ($155,083.82)—by date, showing peaks in July ($37,027.73) and December ($35,211.17) and a low in May ($17,195.63), by payment rating with cash and e-wallets leading over credit cards, by city with Naypyitaw ($110,569) generating the highest sales, by customer type with members ($164,223) contributing more than normal customers, by product line where Food & Beverages ($56,148.84) leads followed by sports & travel ($5,122.83) and electronic accessories ($4,537.53), and by branch with Branch C ($110,568.71) slightly outperforming Branch A ($106,200.37) and Branch B ($106,197.67), all while offering interactive filtering options for branches, product lines, customer types, and payment methods.

**Data Source:**
The data for this analysis likely originates from an internal company database, tracking sales transactions from various branches, customer types, and product lines. It may have been extracted from a Point of Sale (POS) system, Customer Relationship Management (CRM) software, or financial records maintained by the organization.

**Data Collection Process:**

The data was gathered through an automated process, integrating sales transactions recorded from digital payment systems, membership programs, and branch reports. Some data, such as payment ratings, could have been collected through customer feedback surveys.


**The dataset is structured in a tabular format, where:**


•	Rows represent individual sales transactions or aggregated sales summaries by branch, city, or product category.
 
•	Columns capture key variables such as date, sales amount, branch, city, product line, customer type, payment method, and gender.


**Important Features and Their Significance:**

1.	Sales Amount by Gender – this will help understand which gender group contributes more to total sales, assisting in targeted marketing strategies.
2.	Sales Amount by Date –by highlighting this seasonal trends and peaks, it can help inform future sales strategies and promotional campaigns.
3.	Payment Type by Rating – This provides insights into customer preferences for payment methods and their satisfaction levels, which can guide improvements in payment options.
4.	Sales Amount by City –it enables us know how different cities contribute to total revenue, assisting in location-based marketing efforts.
5.	Total Amount by Customer Type –this help Differentiate between members and normal customers, revealing the impact of membership programs on sales.
6.	Sales Amount by Product Line – by Identifying best-performing product categories, it will help the company focus on high-demand products.
7.	Sales Amount by Branch – by evaluating performance across different branches, it wil enable the replication of successful strategies in underperforming locations.

   
**Data Limitations or Biases**

**1.	Sample Bias:**
*My data primarily reflects existing customers and sales transactions, meaning it may not account for potential customers who did not make purchases.
*My dataset is based on specific branches and cities, which may not represent the entire market or consumer behavior across different regions.


**2.	Timeframe Limitations:**

*My data is based on sales performance in 2019, meaning external factors like economic shifts, inflation, or post-pandemic consumer behavior changes in later years are not reflected.

*Seasonal variations (e.g., holiday sales spikes) might skew interpretations if annual trends are not considered.


**3.	Payment and Customer Type Bias:**

*Cash payments are reported as the most used method, but this could be influenced by limited availability of digital payment options rather than actual customer preference.

*Membership-based sales are higher, which could mean non-members are less incentivized to make large purchases due to lack of discounts or benefits.


**4.	Product Line Categorization Issues:**

*Some product categories, such as "Food & Beverages" and "Sports & Travel," dominate sales. This could be due to their essential nature rather than superior sales strategies.

*Other product lines with low sales data may be undervalued, even if they have high profit margins.


**5.	Branch Performance Variability:**

*Branch C outperforms others, but the dashboard does not indicate whether this is due to higher foot traffic, better location, pricing strategies, or customer preferences.

*There might be operational factors (e.g., marketing spend, promotions, staff performance) that skew the sales differences between branches.



**1. Data Cleaning:**

**•	Duplicate Removal:** 

The dataset downloaded from kaggle was properly checked for duplicate transactions to prevent inflated sales figures.


**•	Standardizing Formats:**

I ensured consistency in date formats, product categories, and customer types to facilitate accurate analysis.


**•	Excel Functions:**  


I used tools like IFERROR, VLOOKUP, and AVERAGEIF which was used to handle gaps efficiently.


**. Data Transformations:**

**Aggregation:**

Sales data was grouped by month, city, and customer type to generate meaningful insights.


**New Variables:**

Metrics such as sales growth, percentage contributions of payment methods, and customer retention rates would be computed next time.


**. Data Splitting:**

•	Dependent Variable: Total sales amount, which is influenced by various factors.

•	Independent Variables: Product category, branch, customer type, city, and payment method, as these influence the sales figures.


**. Industry Context:**

•	 The data is from a multi-branch retail company, with insights that are relevant for store operations, marketing, and sales strategy optimization.


**. Stakeholders Benefiting from Analysis:**

•	Marketing Team: They can leverage insights on high-performing products, seasonal trends, and customer behavior for better targeting.

•	Operations & Supply Chain: This can help manage inventory more effectively based on demand fluctuations.

•	Senior Management: The information gotten can be used to strategize branch expansions, promotions, and pricing adjustments.

•	Finance Department: It gives clearer understanding of  sales trends and profitability for budget planning.



**. Value to the Industry:**

•	By optimizing product offerings, it can help determine which product categories are most profitable.

•	By enhancing Customer Experience, it helps for easy understanding payment preferences and loyalty program effectiveness which can leads to better engagement.

•	The competitive Advantage allows the company to stay ahead by leveraging sales trends and customer preferences for long-term growth.



**. Key Trends:**

**•	Seasonal Sales Spikes:**

*Sales show peaks in early February and March, suggesting increased customer activity, possibly due to promotional campaigns or seasonal demand.

*January recorded the highest sales among all months, indicating a strong start to the year.



**•	Regional Performance:**

*Naypyitaw leads in total sales ($110,568.71), surpassing Yangon and Mandalay. This suggests higher customer demand or better sales strategies in this city.

*Branch C outperforms Branches A and B in terms of sales, indicating a stronger market presence or more effective customer engagement.


**•	Best-Selling Product Categories:**

*Food & Beverages generate the highest sales ($56,144.84), followed closely by sports and travel ($55,122.83), showing strong demand for essential and lifestyle-related products.

*Categories like fashion accessories and home & lifestyle also contribute significantly but at lower levels.


**•	Customer Spending Behavior:**

*it’s obvious that members spend more than non-members ($164,223 vs. $158,743), indicating that loyalty programs drive higher purchases.

*From my observation, cash remains the most preferred payment method, followed closely by E-Wallets, while credit cards have a slightly lower rating.


**. Potential Correlations:**

•	From membership and sales, the higher spending by members suggests that loyalty programs and exclusive discounts may effectively drive repeat purchases.

•	From branch location & performance, Branch C and Naypyitaw suggests that customer density, marketing strategies, or regional preferences significantly influence sales.

•	From payment preferences & convenience, they have nearly equal preference for cash and E-Wallets suggests a potential shift toward digital payments, which could be leveraged through targeted incentives.


**. Initial Insights & Questions Raised:**

•	Why does Naypyitaw have higher sales? Does this result from better promotions, a higher customer base, or favorable local conditions?

•	What causes the sales spikes in February and March? Are there specific promotions or seasonal factors influencing this trend?

•	How can the success of Branch C be replicated in other branches to boost sales performance?

•	Can digital payments be further encouraged? Offering incentives for E-Wallet and credit card transactions could drive a shift toward faster and more secure transactions.


**. Unconfirmed Insights (Hypotheses Yet to Be Verified):**


**•	Higher Sales in Naypyitaw:**

*Naypyitaw leads in total sales, surpassing Yangon and Mandalay. This could be due to higher customer traffic, regional demand trends, or more effective marketing strategies. Further data analysis is needed to confirm if this trend is consistent over time or influenced by specific promotions.


**•	Seasonal Sales Spikes in February and March:**

*There are noticeable sales peaks in early February and March, suggesting increased customer activity. This could be linked to seasonal promotions, local holidays, or external market conditions. 

*A closer examination of promotional campaigns during these months is required to validate this hypothesis.


**•	Branch C's Outstanding Performance:**

*Branch C outperforms Branches A and B. Possible factors include better customer engagement, strategic promotions, or an advantageous location. A detailed review of branch-specific strategies can clarify what is driving this success.


**•	Loyalty Program Effectiveness:**

*Members contribute more to total sales than non-members. While this suggests that loyalty programs drive repeat purchases, further analysis is needed to determine whether the higher spending is due to better deals for members or a higher frequency of visits.



**. Recommendations Based on Insights:**

**•	Expand High-Performing Product Categories:**

*Given the strong sales in Food & Beverages and Sports & Travel, the introduction of new products, limited-time offers, or combo deals would help maximize revenue.


**•	Investigate Seasonal Sales Spikes:**

*I feel Conducting further analysis on why February and March would see sales increases and consider replicating those factors throughout the year using targeted marketing campaigns and exclusive product launches.


**•	Replicate Branch C’s Strategy Across Other Locations:**

*I feel if we Study the factors contributing to Branch C’s success and implement similar sales tactics in Branches A and B it will enhance overall performance.


**•	Enhance Loyalty Programs:**

*By Strengthening member-exclusive benefits, such as personalized discounts, cashback rewards, and exclusive promotions, to further boost repeat purchases.


**•	Promote Digital Payment Adoption:**

*Since cash and E-Wallet payments are preferred over credit cards, offering discounts or incentives for digital payments could accelerate the transition to a more efficient and secure transaction process.


**. Analysis Techniques Used in Excel:**

•	Pivot Tables was used to summarize sales data by branch, product line, customer type, and payment method, allowing for quick trend identification.

•	Advanced Formulas like (VLOOKUP, HLOOKUP, INDEX-MATCH) was applied to cross-reference product categories, branch performance, and customer segments.

•	Conditional Formatting helped in Highlighting key trends such as highest sales periods and top-performing branches.

•	Charts & Graph was also used to visualize sales trends over time, customer spending habits, and product category performance.

•	Data Filtering & Sorting was used to enable quick comparisons of sales across different locations and customer segments.


**. Main Takeaways from the Analysis:**


**•	Branch C is the Best Performer:**

*Sales in Branch C (110,568.71) are significantly higher than in Branch A (106,200.37) and Branch B (106,197.67), making it the most successful location.

*This suggests that Branch C's customer engagement, sales strategy, or location factors contribute to higher revenue.


**•	Highest Sales Occurred in January 2023:**

*Sales peaked in January 2023, indicating potential seasonal demand, successful promotions, or holiday shopping effects.

*Further research is needed to identify whether this is a recurring pattern or a one-time spike.


**•	Food & Beverages is the Best-Selling Product Line:**

*The Food & Beverage category leads sales (56,144.84), followed by Sports & Travel (51,122.83).

*This suggests a strong customer preference for consumables and travel-related products, which could guide future inventory and marketing strategies.


**•	Cash is the Most Used Payment Method:**

*While E-Wallets and credit cards are used, cash remains dominant.

*Encouraging more digital payments could improve efficiency, transaction security, and data tracking.


**•	Members Spend More Than Non-Members:**

*Sales from loyalty program members ($164,223) exceed those from non-members ($158,743)

*This reinforces the importance of loyalty programs in increasing repeat purchases.


**•	Sales Spikes in February and March:**

*There is a significant increase in sales in February and March which suggests that targeted marketing campaigns or seasonal trends drive customer spending.

*These spikes should be further analyzed to determine if they can be replicated in other months.


**. Comparison with Initial Expectations:**

•	Branch C’s Success Was Expected, but the Margin Was Higher Than Anticipated meaning the initial insights suggested that Branch C might perform well, but its lead over Branches A and B was more significant than expected.

•	The Popularity of the Food & Beverage Category Aligns with Initial Assumptions which means that Food & Beverages would be a top-performing category, and the analysis confirmed this.

•	Sales Spikes in February and March Were Unexpected Initially, January was identified as the peak sales month, but further analysis revealed that February and March also experience strong sales. This then suggests potential seasonal or promotional factors at play that should be explored further.

•	The Dominance of Cash Transactions Was Not Initially Expected, It was assumed that E-Wallets or credit cards might be more widely used, but cash remains the preferred method, This then presents an opportunity to increase digital payment adoption through discounts or incentives.



**PRE-ANALYSIS**

![Screenshot 2025-03-19 092059](https://github.com/user-attachments/assets/8c030b41-5e9a-42c5-92b0-3d99adab5b74)


Before building the charts, I conducted a pre-analysis to better understand the dataset and guide my storytelling process. This involved breaking down the data into meaningful components


****Project Split:**

I categorized the data points into dependent and independent variables, helping me understand the relationships within the dataset and what types of insights could be extracted. 


**Potential Analysis & Questions:** 

From the grouped variables, I generated key questions that the dataset could answer. This step highlighted the potential insights hidden within the data, even before visualizing it. 


**Preliminary Insights:**


By thinking through the questions and data points, I uncovered early insights, which made it easier to shape the narrative and focus the analysis on valuable outcomes. 


**Storytelling:**

Once I had a clear understanding of the dataset, I could tell a story from it. By putting together the relationships between the datapoints and the insights uncovered. Industry & Stakeholders: This process helped me identify the relevant industry, the stakeholders who would benefit from the analysis, and what success would look like for the organization based on the findings.


**TOTAL AMOUNT BY CUSTOMER TYPE**


![Screenshot 2025-03-19 091540](https://github.com/user-attachments/assets/52b126c4-c2ee-4756-8119-b2c5d038a7ee)

The data indicates that members generate higher total sales ($164,223) compared to non-members ($158,743), suggesting that loyalty programs may positively influence spending behavior, but the margin is relatively small, highlighting potential opportunities to further differentiate member benefits to maximize customer retention and revenue growth.


**SALES AMOUNT BY DATE**

![image](https://github.com/user-attachments/assets/0581b92c-b7c8-4009-ba3e-d5c5b7df0aea)

The sales trend exhibits significant fluctuations, with a peak in January ($43,644.55) followed by a decline in mid-year (June: $17,195.63) and a secondary peak in September ($37,027.73), suggesting potential seasonality or external factors influencing purchasing behavior, while the sharp drop in November ($13,490.79) and December ($15,211.17) may indicate a need for targeted promotions to boost year-end sales.


**SALES AMOUNT BY GENDER**

![image](https://github.com/user-attachments/assets/b6eed6ac-2621-415d-b094-3017a3dda15e)

The sales distribution by gender shows that female customers contributed slightly more ($167,882.93) than male customers ($155,083.82), indicating a near-balanced purchasing behavior but with a marginally higher engagement or spending tendency among female buyers, which could inform targeted marketing strategies.


**SALES AMOUNT BY PRODUCT LINE**

![image](https://github.com/user-attachments/assets/a488c79d-2992-4669-bd37-660f63964c42)

The Food and Beverages category leads in total sales ($56,144.84), followed closely by Sports and Travel ($55,122.83) and Electronic Accessories ($54,337.53), while Health and Beauty ($49,193.74) has the lowest sales, suggesting that demand is relatively balanced across product lines, but promotional efforts could focus on boosting lower-performing categories.


**PAYMENT TYPE BY RATING**

![image](https://github.com/user-attachments/assets/f1c6b49c-e0bc-4a0e-95e5-48304b0dd7c5)

The Cash (2,397.70) and E-wallet (2,397.00) payment methods received the highest ratings, while Credit Card (2,178.00) had the lowest, suggesting that customers may find cash and digital wallets more convenient or reliable, whereas credit cards may have certain drawbacks such as processing time or fees.


**SALES AMOUNT BY CITY**

![image](https://github.com/user-attachments/assets/2c811878-3dd6-439b-be96-80270455338e)

The sales distribution across cities shows that Naypyitaw ($110,569) had the highest sales, followed closely by Yangon ($106,200) and Mandalay ($106,198), indicating a relatively balanced sales performance across all three cities with only a slight advantage in Naypyitaw.


**SALES AMOUNT BY BRANCH**

![image](https://github.com/user-attachments/assets/46252b7e-1397-4e13-bd62-a20207baa317)

Branch C recorded the highest sales at $110,568.71, while branches A ($106,200.37) and B ($106,197.67) had almost identical sales figures, indicating a relatively balanced sales distribution across the branches, with only a slight lead by Branch C.


**FINAL RECOMMENDATION**

![Screenshot 2025-03-19 092514](https://github.com/user-attachments/assets/0dea4f03-3a90-4cf6-af67-33bfca2318dc)


**Recommendations**

Leverage Branch C’s Success: Analyze its customer traffic, sales strategies, and promotional efforts to replicate the model in Branch A and B for enhanced sales performance.

Expand Food & Beverage Offerings: Introduce new products, limited-time deals, or combo promotions to capitalize on customer demand and boost revenue.

Enhance Loyalty Programs: Provide personalized discounts, cashback rewards, and exclusive offers to increase customer engagement and spending.

Encourage Digital Payments: Offer incentives for E-wallet and credit card transactions to drive a shift toward cashless payments, enhancing security and efficiency.


**Market-Specific Strategies**

Identify Seasonal Sales Trends: Understand the factors behind February and March sales spikes and apply similar strategies year-round through targeted campaigns and exclusive product launches.

City-Specific Marketing: Strengthen presence in Naypyitaw while identifying growth opportunities in Yangon and Mandalay through localized promotions and partnerships.

Gender-Specific Campaigns: Develop marketing strategies tailored to both male and female customers to ensure balanced brand appeal and maximize sales across demographics.

![image](https://github.com/user-attachments/assets/61294316-80cd-4715-8d22-f896ae6b4453)


**Key Observations**

**Branch C’s Performance:** Branch C outperformed all other branches with total sales of $110,568.71, indicating higher customer engagement or a larger volume of transactions compared to Branch A and B.

**Top-Selling Category:** Food & Beverages generated the highest revenue at $56,144.84, highlighting its popularity as a frequently purchased category.

**Impact of Memberships:** Members accounted for a significant share of sales, contributing $164,223.44, demonstrating that loyalty programs effectively drive higher spending.

**Preferred Payment Methods:** Cash remained the dominant payment method, followed by E-wallets and credit cards, suggesting that either traditional payment preferences persist or digital payment adoption is still developing.

**Seasonal Sales Trends:** Sales spiked notably in February and March, reaching $35,770.60 and $38,678.46, respectively, compared to more stable numbers in January. This indicates a possible influence of seasonal demand or marketing efforts.

**Sales by City**: Among the three cities, Naypyitaw led with the highest revenue ($110,568.71), closely followed by Yangon ($106,200.37) and Mandalay ($106,197.67), showing relatively even sales distribution but with a slight edge for Naypyitaw.

**Gender-Based Spending Patterns:** Male customers spent slightly more than females, with total expenditures of $167,882.93 compared to $155,083.82, suggesting potential differences in purchasing behavior or product preferences.


**CONCLUSION**

The 2019 sales analysis reveals that Branch C had the highest revenue, with Food & Beverages as the top-selling product category. Cash was the most preferred payment method, though digital transactions are growing. Loyalty programs significantly boosted sales, with members contributing more than normal customers. Male customers spent slightly more than females, and Naypyitaw led in city-based sales. Seasonal demand drove revenue spikes in early months, while some months saw declines. To sustain growth, businesses should replicate successful sales strategies, enhance loyalty programs, expand high-performing product lines, and implement targeted marketing campaigns.



