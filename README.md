# First Bank Term Deposit Campaign Analysis 2024

## Project Overview
This dataset contains detailed records from a First Bank marketing campaign aimed at encouraging customers to subscribe to a term deposit product. The data includes customer demographics, financial attributes, and historical campaign interactions.

---

## Objective:
Evaluate customer behavior, assess what drove campaign effectiveness, and surface insights that sharpen future, data-driven targeting.

---

## Business Problem
First Bank needed to understand which customers were most likely to subscribe to the term deposit product and which campaign strategies were most effective. The analysis aimed to identify customer characteristics, financial factors, communication methods, and campaign behaviors associated with subscription so that future campaigns could be better targeted.

**The analysis addressed questions such as:**

- Which customer demographics have the highest subscription rates?
- How does subscription behavior vary across customer groups and occupations?
- How do balance levels and loan status affect term-deposit subscription?
- Which contact methods generate more subscriptions?
- How does the number of campaign contacts affect subscription?
- Does call duration differ between subscribers and non-subscribers?
- What relationships exist between age, balance, call duration, and campaign contacts?
- Which months showed stronger or weaker campaign performance?
- Which customer segments should receive greater attention in future campaigns?

---

## Dataset Overview
 <img width="1412" height="739" alt="image" src="https://github.com/user-attachments/assets/6e497795-c0ce-4683-b7ee-c329c8074d64" />

---

## Data Quality Assessment & Preparation
The raw dataset is clean structurally (zero nulls, zero duplicate rows across all 11,162 records) but carries several “unknown” placeholder values that need deliberate handling rather than blind deletion.

 <img width="1090" height="394" alt="image" src="https://github.com/user-attachments/assets/c23fcbf4-52fd-4d97-b4cb-eaa0a041e1e7" />

---

## Customer Group Comparison Using Visual Analytics
- Customers in Management recorded the highest subscription rate (11.73%), making them the most responsive occupation group in the marketing campaign.
- Technicians demonstrated a high subscription rate (7.57%), indicating they are one of the bank's most promising customer segments.
- Although Blue-Collar customers represent a large portion of the campaign, a significantly higher percentage did not subscribe (11.14%) compared to those who did (6.38%), suggesting lower campaign effectiveness within this group.
- Students (2.43%) and Retired customers (4.65%) have a higher proportion of subscriptions than non-subscriptions, indicating these groups are relatively more receptive to the term deposit offer despite their smaller population sizes.
  
 <img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/2bdf1e86-39d6-4d52-8b1b-7ec99775bcaf" />

---

## Impact of Financial Profile on Marketing Outcomes
Low Balance customers had the highest subscription rate at about 58%, followed by Medium Balance customers at about 34%. High Balance customers had the lowest subscription rate at around 8%. This suggests that customers with lower balances were more likely to subscribe to the term deposit than customers with higher balances.
#### This could be happening for several reasons:
- Low-balance customers may be more interested in growing their savings through a term deposit, making them more responsive to the campaign.
- High-balance customers may have other investment options, so they may be less interested in this particular product.
- The campaign may have been more effective at reaching low-balance customers through its targeting or messaging.
- Other factors could be influencing the result, such as age, job, loans, previous campaign response, and contact frequency.
  
 <img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/5da9f2be-2ae3-4368-aa94-0ce6208f2203" />

---

## Evaluation of Contact Strategy Effectiveness
Cellular contact generated far more term-deposit subscriptions than telephone contact, with 4,369 customers subscribing through cellular compared with 390 through telephone. This could be because cellular communication is more accessible and convenient for customers, making them more responsive to the campaign. Overall, the campaign appears to have reached and converted more customers through the cellular channel.

 <img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/84157dad-304c-4430-b1da-7d680d74e220" />

---

## Temporal Performance and Feature Engineering and Segment Analysis 
 <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/ba4eb502-58f4-4183-8bf5-5d95d272bb66" />

---

#### When to run the next campaign 
The marketing campaign achieved its highest subscription rate in May and maintained relatively strong performance through June to August, while March, September, and December recorded the lowest subscription levels. Overall, customer subscriptions consistently exceeded non-subscriptions across all months, although campaign performance showed noticeable seasonal fluctuations.

<img width="800" height="300" alt="image" src="https://github.com/user-attachments/assets/a97e99ff-aa52-4a61-ae2b-1182052166f6" />

---

## Dashboard Summary
The dashboard brings together the campaign's key performance indicators and customer segmentation analysis. It shows term-deposit subscription performance across demographics, financial profiles, contact methods, campaign interaction, and time, allowing users to identify patterns in customer conversion.

Key dashboard areas include:

- **Subscription performance:** 47.38% of contacted customers subscribed.
- **Customer demographics:** Subscription patterns by age, marital status, education, and occupation.
- **Financial profile:** Subscription patterns across balance groups and loan ownership.
- **Contact strategy:** Comparison of subscription outcomes by communication channel.
- **Campaign interaction:** Analysis of contact frequency and call duration.
- **Time trends:** Monthly variations in campaign subscription performance.
- **Customer segmentation:** Age, balance, call-duration, and campaign-interaction groups.

<img width="1000" height="612" alt="image" src="https://github.com/user-attachments/assets/0eaac50b-89d3-46b1-b38e-988c68442f79" />

---

## Key Insights
- **47.38% Overall Subscription —** Nearly half of contacted customers subscribed to the term deposit.
- **Previous Subscribers Showed Strong Conversion —** Customers who had subscribed in a previous campaign recorded a 91.3% conversion rate.
- **High-Balance Customers Converted More —** 57.2% of high-balance customers and 55.3% of medium-balance customers subscribed, compared with 42.7% of low-balance customers.
- **Contact Frequency Matters —** Customers contacted 1–3 times showed the strongest conversion, while those contacted 7+ times had the lowest conversion at 22.4%.
- **Call Duration Signals Interest —** Subscribers spent an average of 537 seconds on calls compared with 223 seconds for non-subscribers.
- **Cellular Performed Better —** Cellular contacts achieved a 54.3% subscription rate, compared with 50.4% for telephone.
- **Occupation Influenced Subscription —** Management customers had the highest subscription proportion at 11.73%, followed by Technicians at 7.57%.
- **Financial Commitments Matter —** Customers with housing or personal loans were less likely to subscribe according to the analysis.
- **Campaign Performance Varied by Month —** May recorded the strongest subscription performance, while March, September, and December recorded lower levels.
- **Numerical Variables Alone Do Not Explain Subscription —** Age, balance, and call duration showed weak or no correlations with one another, suggesting that combinations of customer and campaign characteristics are more informative.

---

## Recommendations 
1. **Prioritize Previous Subscribers**
   Focus on customers with a history of successful term deposit subscriptions, as they showed strong conversion rates.
2. **Target Suitable Financial Segments**
   Prioritize customers with higher balances and fewer outstanding financial commitments.
3. **Limit Excessive Contact**
   Avoid repeated calls to the same customers, as high contact frequency was associated with lower subscription rates.
4. **Focus on Conversation Quality**
   Use call duration as an engagement indicator and prioritize meaningful customer conversations over frequent calls.
5. **Expand Cellular Outreach**
   Increase the use of cellular communication, which recorded a higher subscription rate than telephone contact.
6. **Use Customer Segmentation**
   Tailor campaigns based on customer demographics, occupation, financial profile, and previous campaign behavior.
7. **Improve Low-Response Segments**
   Develop targeted messaging and engagement strategies for customer groups with lower subscription rates.
8. **Use Seasonal Campaign Planning**
   Consider monthly subscription patterns when planning future campaigns and allocating marketing resources.
9. **Monitor Campaign Fatigue**
   Track the relationship between contact frequency and subscription outcomes to prevent over-contacting customers.
10. **Adopt Data-Driven Targeting**
    Combine demographic, financial, and campaign interaction data to identify customers who are more likely to subscribe.

---

## Conclusion 
This project analyzed Fidelity Bank customer transaction data to uncover patterns in customer demographics, spending behavior, account balances, and geographic transaction activity. The dataset was cleaned and prepared by validating data quality, deriving customer age and age groups, standardizing formats, and ensuring consistency for accurate analysis.

An interactive dashboard was developed to visualize customer spending trends, demographic distributions, balance segments, and location performance, enabling stakeholders to monitor key performance indicators and customer behavior effectively. Overall, the findings demonstrate how customer segmentation and transaction analytics can support targeted marketing, improve customer retention, optimize branch operations, and drive data-informed strategic decision-making for Fidelity Bank.

---

