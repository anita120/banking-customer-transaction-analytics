# Business Insights

## Banking Customer & Transaction Analytics

**Analysis period:** January–December 2025  
**Dataset:** Synthetic banking customer and transaction data  
**Tools:** SQL, Python/pandas, Power BI

---

## Executive Summary

The analysis covers 5,000 customers and 120,000 transactions with a total transaction value of approximately ₹228.76 million during 2025.

The analysis indicates a customer activity rate of 76.78%, with most active customers falling into the Moderate or High Activity groups. UPI was the highest-volume transaction channel, while monthly transaction activity remained relatively stable throughout the year. The Mass customer segment generated the largest absolute transaction value, broadly consistent with its larger customer population.

---

## Key Business Insights

### 1. Customer engagement

Of the 5,000 customers in the dataset, 3,839 were active during 2025, resulting in an overall activity rate of **76.78%**. The remaining 1,161 customers had no recorded transaction activity during the year.

**Business implication:**  
The inactive customer population represents a potential area for investigation and re-engagement. Further analysis would be needed to understand why these customers were inactive and whether they remain relevant to the bank.

---

### 2. Activity is concentrated in Moderate and High Activity customers

Among active customers:

- Low Activity: 122 customers
- Moderate Activity: 2,030 customers
- High Activity: 1,408 customers
- Very High Activity: 279 customers

Moderate and High Activity customers together represent **89.56% of active customers**.

**Business implication:**  
Customer engagement is broadly distributed among regularly active customers rather than being concentrated only among a small group of very-high-frequency users.

---

### 3. UPI is the highest-volume transaction channel

UPI recorded **40,909 transactions**, representing approximately **34.1% of all transactions**. It was followed by Mobile App with 23,970 transactions and Internet Banking with 19,239 transactions.

Average transaction values were relatively close across channels, ranging from approximately ₹1,867 to ₹1,929.

**Business implication:**  
The major difference between channels is transaction volume rather than transaction size. The dataset therefore indicates strong usage of digital transaction channels, particularly UPI.

---

### 4. Monthly transaction activity remained relatively stable

Monthly transaction volume ranged from approximately **9,247 transactions in February** to **10,505 transactions in August**.

August recorded the highest transaction volume, while February recorded the lowest. However, there was no strong sustained upward or downward trend during 2025.

**Business implication:**  
The dataset does not show a strong annual growth or decline pattern in transaction volume. Month-to-month fluctuations may warrant further investigation if additional information such as campaigns, holidays, or seasonal events becomes available.

---

### 5. Mass customers generated the largest transaction value

Transaction value by customer segment was:

| Segment | Customers | Transaction Value | Share of Transaction Value |
|---|---:|---:|---:|
| Mass | 3,071 | ₹140.72M | 61.5% |
| Affluent | 1,442 | ₹66.15M | 28.9% |
| Premium | 487 | ₹21.88M | 9.6% |

The distribution of transaction value broadly follows the distribution of customers across the three segments.

Average transaction values were also relatively similar:

- Affluent: ₹1,913.57
- Mass: ₹1,909.56
- Premium: ₹1,864.51

**Business implication:**  
In this dataset, absolute transaction value appears to be influenced more by customer population and transaction frequency than by large differences in average transaction size between segments.

---

## Overall Business Takeaways

1. **Customer engagement:** 76.78% of customers were active during 2025, while 23.22% recorded no transaction activity.
2. **Activity depth:** 89.56% of active customers were in the Moderate or High Activity groups.
3. **Channel usage:** UPI was the largest transaction channel by volume, accounting for approximately 34.1% of transactions.
4. **Transaction stability:** Monthly transaction volume remained within a relatively narrow range throughout the year.
5. **Segment contribution:** The Mass segment generated the largest absolute transaction value, broadly reflecting its larger customer population.

---

## Analytical Limitations

This project uses a **synthetic dataset created for portfolio and demonstration purposes**. The findings should therefore not be interpreted as representing the behavior or performance of a real bank.

The dataset also does not contain:

- Customer revenue or profitability
- Transaction fees
- Customer acquisition cost
- Product-level transaction identifiers
- Fraud labels
- Campaign information
- Customer satisfaction or churn indicators

Because transactions do not contain a `product_id`, transaction value cannot be reliably attributed to individual banking products. Product analysis should therefore focus on customer product adoption rather than product-level transaction value.

High-value transactions should also not automatically be interpreted as suspicious or fraudulent because the dataset contains no fraud labels or investigation outcomes.

---

## Recommended Next Analyses

If additional business data were available, the following analyses could extend this project:

- Customer retention and churn analysis
- Customer profitability analysis
- Product adoption and cross-sell analysis
- Channel migration analysis
- Fraud/anomaly detection using labeled transaction outcomes
- Customer lifetime value analysis
- Cohort analysis based on customer join date

---

## Tools Used

- **SQL / PostgreSQL:** Data validation, joins, aggregations, segmentation and business analysis
- **Python / pandas:** Data preparation, exploratory data analysis and customer-level analysis
- **Power BI:** Interactive dashboard, KPI reporting and visual analysis
