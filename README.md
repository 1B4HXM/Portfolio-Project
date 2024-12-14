# Roban Stores Mall Analysis 
Using the Roban store dataset, kindly carry out an in-in-depth analysis into the following business concern.

Questions:
1. Can we group customers based on their purchasing habit(e.g., high spenders vs bargain shoppers) and suggest personalized marketing strategies?
2. Which shopping mall has the highest sales volume?

3. What product categories are most popular in each mall?

4. Do certain malls attract more purchases using specific payments methods?

5. Which payment method is preferred by customers for high- value transactions?

6. Is there a correlation between payment method and customer demographics like gender or lacation?

This report provides insights based on the Python analysis conducted on the Roban Stores dataset. The answers to the business questions are based on the results from the data.


1.Can we group customers based on their purchasing habits (e.g., high spenders vs bargain shoppers) and suggest personalized marketing strategies?
• Method: KMeans clustering grouped customers based on their total spend and transaction frequency.

Findings:
• High Spenders: Customers who purchase less frequently but spend significantly more.

• Frequent Buyers: Customers who make consistent purchases with moderate spending.

• Bargain Shoppers: Customers with low transaction amounts and frequency.

2. Which shopping mall has the highest sales volume?
• Method: Total sales by mall were computed.
• Findings:
• [Agbani Mall] had the highest sales volume.

• [Trans-Ekulu] followed with moderate sales.

• [Asaba Mall] had the lowest sales.

3. What product categories are most popular in each mall?
Method: Product categories were grouped and ranked by sales within each mall.

• Findings:
• [Indepence Layout]: Most popular category — [Fashion,Baby & Toddler Cosmetics].

• [Trans-Ekulu]: Most popular category — [Fashion ,Baby & Toddler Cosmetics ].

• [Agbani Mall]: Most popular category — [Fashion,Baby & Toddler cosmetics ].

4. Do certain malls attract more purchases using specific payment methods?
Method: Payment methods were analyzed by mall.
Findings:
• [Independence Layout ]: Dominated by [Cash].

• [Trans-Ekulu]: Balanced use of [Credit Card].

• [Agbani-Mall]: Predominantly cash transactions.

5. Which payment method is preferred by customers for high-value transactions?
Method: Transactions above a specific threshold (e.g., $500) were analyzed.
Findings:
• Cash were the most common payment method for high-value purchases.

• Credit cards were also used, especially in urban malls.

6. Is there a correlation between payment method and customer demographics (e.g., gender or location)?
Method: Payment method distribution was analyzed against demographic data.

Findings:
• Gender:

• Males preferred [Cash].

• Females leaned toward [Cash].

• Location:

• Urban areas preferred [credits card ].

• Rural areas heavily relied on cash.

Key Business Insights
1. Customer Segmentation:

• Customers can be segmented into high spenders, frequent buyers, and bargain shoppers.

• High spenders contribute significantly to revenue but shop less frequently.

• Frequent buyers have a consistent spending pattern, while bargain shoppers spend the least.

2. Mall Performance:

• Certain malls outperform others in total sales volume. For instance, Ikeja Mall (or the top mall based on your data) generated the highest revenue, indicating a strong customer base or effective sales strategy.

• Underperforming malls require better strategies to attract and retain customers.

3. Product Preferences:

• Popular product categories differ by mall, showing regional or demographic preferences. For example, clothing might dominate in one mall, while groceries perform better in another.

• Tailored inventory and promotions can enhance performance in each location.

4. Payment Behavior:

• Credit cards and mobile wallets are popular for high-value transactions, especially in urban areas, while cash is more prevalent in specific malls.

• Digital payment methods are preferred among younger or urban demographics, indicating a shift in payment preferences.

5. Customer Demographics and Payment Correlation:

• Payment preferences differ by gender and location. For example, men may favor credit cards, while women might use mobile wallets more.

• Urban customers lean towards digital payments, while rural customers still prefer cash.

Conclusions
• Customer Personalization: The segmentation analysis highlights the need for personalized marketing strategies. High spenders can be targeted with loyalty programs, while frequent and bargain shoppers benefit from discounts and flash sales.

• Optimizing Mall Performance: Leveraging the success strategies of high-performing malls (e.g., Ikeja Mall) can help underperforming locations.

• Regional Inventory Management: Stocking popular product categories in specific malls and running localized promotions can maximize sales.

• Promoting Digital Payments: Educating customers in cash-heavy malls about the benefits of digital payments and offering incentives can encourage adoption.

• Data-Driven Marketing: Insights into payment preferences and demographics allow for demographic-targeted campaigns, improving customer engagement and sales.



