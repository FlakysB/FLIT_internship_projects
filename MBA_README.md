# MARKET BASKET ANALSIS FOR E-COMMERCE

<img width="476" alt="MBA JPEG" src="https://github.com/FlakysB/FLIT_internship_projects/assets/138071820/e20a155e-9ae6-4175-9166-de3f559b39f0">

# TASK
To perform market basket analysis to uncover patterns in customer purchasing behavior. By identifying which products  tend  to  be  bought  together, 
to help e-commerce company make informed  decisions  to  improve  sales  and  customer satisfaction.

# OBJECTIVE
The goal of this project is to gain experience on the concept of market basket analysis, which is a crucial aspect of data science in retail and e-commerce. 
which will give exposure on how to extract valuable insights from transaction data, understand customer purchasing behaviour, 
and use this knowledge for business optimization.

# WHAT IS MARKET BASKET ANALYSIS(MBA)?
Market Basket Analysis is a method used to find patterns in customer shopping behavior, helping businesses understand which products are often bought together. 
This knowledge can be leveraged to improve the arrangement of products in stores, create targeted marketing campaigns, and enhance overall business strategies.
It is often applied in retail or e-commerce but can be used in various industries where transactions or interactions involve multiple items.


# EXPLAINATION OF TERMS USED IN MBA
1. **Baskets of Items:**
   - Imagine you're at a grocery store, and you have a shopping basket. In this context, each purchase you make is like a "basket" of items.

2. **Association Rules:**
   - MBA is interested in finding patterns or associations among items that tend to be bought together. For example, if customers often buy bread and butter together, there might be an association between these two items.

3. **Frequent Itemsets:**
   - MBA identifies sets of items that frequently appear together in transactions. These sets are called "frequent itemsets."

4. **Support, Confidence, and Lift:**
   - MBA uses metrics like support, confidence, and lift to measure the strength and significance of associations between items.
      - **Support:** How frequently a particular itemset appears in the dataset.
      - **Confidence:** The likelihood that if a customer buys one item (antecedent), they will also buy another item (consequent).
      - **Lift:** Measures how much more likely items are bought together than if they were bought independently.

5. **Example:**
   - Let's say MBA identifies a rule with high confidence, indicating that customers who buy milk are 80% likely to buy cereal as well. This information could be valuable for store owners because it suggests a strong association between these items. They might decide to place milk and cereal close to each other in the store to encourage additional sales.

6. **Business Insights:**
   - The insights gained from MBA can help businesses optimize product placement, marketing strategies, and even make decisions about discounts or promotions to maximize sales and customer satisfaction.

# INTERPRETATION AND INSIGHTS

**Observation:**

In general, when examining association rules, it is noticed that rules with a conviction value greater than or equal to 1 tend to have a positive Zhang's metric. This positive Zhang's metric, which combines both lift and confidence, signifies a strong association between the items involved in the rule and a high level of certainty in the rule's validity.

From the table above it can be observed that the higher the support metrics the Zhang's metric becomes negative which suggests that the observed association is less interesting or meaningful than what would be expected based on the independence of confidence and lift.

**Implication:**
A conviction value of greater than or equal to 1 indicates that the antecedent significantly influences the likelihood of the consequent, strengthening the association between the items.

When this high conviction is coupled with a positive Zhang's metric, it reinforces the idea that the rule is not only strong but also interesting and reliable, as it surpasses what might occur randomly.

**Specific Observations:**

**Rule 13:** Customers buying 'other vegetables' are also buying 'frankfurter.' The lift is slightly above 1, indicating a positive association.

**Rule 59:** 'Yogurt' and 'sausage' have a positive association, but the confidence is relatively low.

**Rule 1:** 'Bottled beer' and 'whole milk' have a slightly negative lift, indicating they are less likely to be bought together than expected.

**Rule 56:** 'Sausage' and 'whole milk' have a negative lift, suggesting they are less likely to be bought together than expected.

It seems that certain items like 'sausage' and 'whole milk' have negative associations with other items, which might be interesting to investigate further.

# RECOMMENDATIONS

**Product Placement:**

'other vegetables' and 'frankfurter' should be considered to be placed together as they show a positive association.

**Marketing Strategies:**

Marketing efforts should be made For 'yogurt' and 'sausage,' to focus on encouraging customers to buy them together, perhaps through promotions or special offers (discounted sales).

**Basket Optimization:**

Rules with negative lift, like 'bottled beer' and 'whole milk' or 'sausage' and 'whole milk.' should be analysed and Considered whether their placements can be adjusted or if there are cross-promotional opportunities.

# NOTE:
Further Investigation should be carried on rules with low confidence and explore factors that might impact these associations.
