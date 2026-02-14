# Customer-Segmentation-Revenue-Analysis-using-RFM-Model
Through this Project i analyzed two datasets of a customers details and their transactions details , which gives insights about customers and about their spending behaviour  like frequency of transaction, how much amount of transaction and   how frequent they do transactions.

The Customers_master Dataset has information about customer like customer_id, Name, Email, Age, Gender, City, Martial Status, Join Date and NumChildren which is Number of children. Whereas Customer_Transaction Dataset has information about customer spending behaviour like customer_ID, Transaction date, Transaction Amount. 

My objective through this project is to know about my customers that which of them spend more, spend frequently and spend regularly. Which is in other term RFM Model Analysis. RFM stand for Rececy, Frequency and Monetary.
● Recency = Days between "today" and last transaction date
● Frequency = Total number of transactions
● Monetary = Sum of all TransactionAmount values

Analyzed 23,000+ transaction records and 1,000 customer profiles to segment customers based on Recency, Frequency, 
and Monetary (RFM) behavior. Built a full RFM scoring system and classified customers into business segments such as 
Champions, Loyal, Potential Loyalists, At-Risk, and Lost. Performed revenue contribution analysis for each segment and 
visualized customer distribution and revenue share to support data-driven marketing and retention strategies.

I assign each customer a score from 1to5 on basis of Recency, Frequency and Monetary.
Example logic:
o Recency: Lower days = higher score (recent buyers)
o Frequency: Higher count = higher score
o Monetary: Higher spend = higher score

After giving score individually on basis of each three paramenter , i combine their score and give each customer a title like
● R=5, F=5, M=5 → "555" Champion
● R=1, F=1, M=1 → "111" Lost

Use the RFM score combinations to define:
● Champions (e.g., RFM 555)
● Loyal Customers
● At Risk
● Hibernating
● Potential Loyalists, etc.
