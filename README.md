# First Bank Term Deposit Campaign Analysis 2024

## Project Overview
This dataset contains detailed records from a First Bank marketing campaign aimed at encouraging customers to subscribe to a term deposit product. The data includes customer demographics, financial attributes, and historical campaign interactions.
### Objective:
Evaluate customer behavior, assess what drove campaign effectiveness, and surface insights that sharpen future, data-driven targeting.

## What This Deck Answers
- Which customers are actually converting and which segments to prioritise
- How financial profile (balance, loans) shapes subscription decisions
- Which campaign tactics (channel, call length, contact frequency) work
- When to run the next campaign, and who to call first

## Dataset Overview
 <img width="1412" height="739" alt="image" src="https://github.com/user-attachments/assets/6e497795-c0ce-4683-b7ee-c329c8074d64" />


## Data Quality Assessment & Preparation
The raw dataset is clean structurally (zero nulls, zero duplicate rows across all 11,162 records) but carries several “unknown” placeholder values that need deliberate handling rather than blind deletion.

 <img width="1090" height="394" alt="image" src="https://github.com/user-attachments/assets/c23fcbf4-52fd-4d97-b4cb-eaa0a041e1e7" />


## Customer Group Comparison Using Visual Analytics
- Customers in Management recorded the highest subscription rate (11.73%), making them the most responsive occupation group in the marketing campaign.
- Technicians demonstrated a high subscription rate (7.57%), indicating they are one of the bank's most promising customer segments.
- Although Blue-Collar customers represent a large portion of the campaign, a significantly higher percentage did not subscribe (11.14%) compared to those who did (6.38%), suggesting lower campaign effectiveness within this group.
- Students (2.43%) and Retired customers (4.65%) have a higher proportion of subscriptions than non-subscriptions, indicating these groups are relatively more receptive to the term deposit offer despite their smaller population sizes.
  
 <img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/2bdf1e86-39d6-4d52-8b1b-7ec99775bcaf" />


## Impact of Financial Profile on Marketing Outcomes
Low Balance customers had the highest subscription rate at about 58%, followed by Medium Balance customers at about 34%. High Balance customers had the lowest subscription rate at around 8%. This suggests that customers with lower balances were more likely to subscribe to the term deposit than customers with higher balances.
#### This could be happening for several reasons:
- Low-balance customers may be more interested in growing their savings through a term deposit, making them more responsive to the campaign.
- High-balance customers may have other investment options, so they may be less interested in this particular product.
- The campaign may have been more effective at reaching low-balance customers through its targeting or messaging.
- Other factors could be influencing the result, such as age, job, loans, previous campaign response, and contact frequency.
  
 <img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/5da9f2be-2ae3-4368-aa94-0ce6208f2203" />


## Evaluation of Contact Strategy Effectiveness
Cellular contact generated far more term-deposit subscriptions than telephone contact, with 4,369 customers subscribing through cellular compared with 390 through telephone. This could be because cellular communication is more accessible and convenient for customers, making them more responsive to the campaign. Overall, the campaign appears to have reached and converted more customers through the cellular channel.

 <img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/84157dad-304c-4430-b1da-7d680d74e220" />


## Temporal Performance and Feature Engineering and Segment Analysis 
 <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/ba4eb502-58f4-4183-8bf5-5d95d272bb66" />


#### When to run the next campaign 
The marketing campaign achieved its highest subscription rate in May and maintained relatively strong performance through June to August, while March, September, and December recorded the lowest subscription levels. Overall, customer subscriptions consistently exceeded non-subscriptions across all months, although campaign performance showed noticeable seasonal fluctuations.

<img width="800" height="300" alt="image" src="https://github.com/user-attachments/assets/a97e99ff-aa52-4a61-ae2b-1182052166f6" />

## Dashboard Summary
<img width="1000" height="612" alt="image" src="https://github.com/user-attachments/assets/0eaac50b-89d3-46b1-b38e-988c68442f79" />


## Recommendations 
 <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/69308cec-dade-40a1-b57e-25b1503cbd01" />


## Conclusion 
This project analyzed Fidelity Bank customer transaction data to uncover patterns in customer demographics, spending behavior, account balances, and geographic transaction activity. The dataset was cleaned and prepared by validating data quality, deriving customer age and age groups, standardizing formats, and ensuring consistency for accurate analysis.

An interactive dashboard was developed to visualize customer spending trends, demographic distributions, balance segments, and location performance, enabling stakeholders to monitor key performance indicators and customer behavior effectively. Overall, the findings demonstrate how customer segmentation and transaction analytics can support targeted marketing, improve customer retention, optimize branch operations, and drive data-informed strategic decision-making for Fidelity Bank.



