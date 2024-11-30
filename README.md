# Market-Basket-Analysis

Market basket analysis is a strategic data mining technique used by retailers to enhance sales by gaining a deeper understanding of customer purchasing patterns.This method involves examining substantial datasets, such as historical purchase records, to unveil inherent product groupings and identify items that customers tend to buy together.

By recognizing these patterns of co-occurrence, retailers can make informed decisions to optimize inventory management, devise effective marketing strategies, employ cross-selling tactics, and even refine store layout for improved customer engagement.

For example, if customers are buying milk, how probably are they to also buy bread (and which kind of bread) on the same trip to the supermarket? This information may lead to an increase in sales by helping retailers to do selective marketing based on predictions, cross-selling, and planning their ledge space for optimal product placement.


Now, just think of the universe as the set of items available at the store, then each item has a Boolean variable that represents the presence or absence of that item. Now, we can represent each basket with a Boolean vector of values assigned to these variables. We can then analyze the Boolean vectors to identify purchase patterns that reflect items frequently associated or bought together, representing such patterns in the form of association rules.

## Key Concepts

#### 1.Transactions: Sets of items bought together, typically recorded in a dataset.
#### 2.Itemsets: Groups of items (e.g., {milk, bread, butter}).
#### 3.Association Rules: If-then statements showing relationships (e.g., "If milk is bought, bread is likely to be bought").
#### 4.Metrics:
##### Support: The frequency of an itemset in all transactions.
       Support(A)=number of transaction containing A/Total Transactions
##### Confidence: Measures the likelihood of purchasing item B when item A is purchased.
       Confidence=Transaction containing both A and B/Transaction containing A
##### Lift: Measures how much more likely two items are to be bought together compared to being bought independently. It accounts for random chance.
       LIFT=Support of A and B/(Support of A*Support of B)
 
## Market Basket Analysis Dashboard
![Screenshot (27)](https://github.com/user-attachments/assets/4ff130b7-ced1-4f6d-abf4-cb33f47a2a1a)

## Insights
1 Root Vegetables Lead the Way: Root vegetables are the most frequently purchased item, with a high support score and strong associations with complementary products like onions and beef. This highlights their central role in driving cross-sales.

2 Strategic Pairing Opportunities: The association between whipped sour cream and berries (with a high lift value) suggests a natural combination. Retailers could create bundled promotions to capitalize on this consumer behavior.

3 High-Impact Products: Items like frozen vegetables and butter show strong relationships, indicating a great opportunity for targeted marketing campaigns or in-store placement strategies to boost sales.
