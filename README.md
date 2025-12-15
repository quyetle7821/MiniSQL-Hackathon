# [SQL] MiniSQL-Hackathon
## I. Introduction
I built this mini project to get hands-on practice with SQL fundamentals and sharpen my problem-solving mindset
## II. Questions
<img width="382" height="173" alt="image" src="https://github.com/user-attachments/assets/d3549a6c-6793-4c67-8cc3-33bab8951092" />

## III. Exploring the Dataset
## 1. Total number of orders by month
- ### Query
  <img width="830" height="159" alt="image" src="https://github.com/user-attachments/assets/acb48efa-c93f-4319-b078-a445801f0811" />
- ### Result
<img width="427" height="223" alt="image" src="https://github.com/user-attachments/assets/ff2b7fc6-beef-4141-9f4a-ef8ca307531a" />

## 2. Number of customers who make purchases each month
- ### Query 
  P/S: I’m calculating the number of unique customers who made a purchase each month, so repeat buyers aren’t counted multiple times. If we counted repeat purchases, the output would be the same as QQ1.
  
<img width="797" height="178" alt="image" src="https://github.com/user-attachments/assets/c77460cf-c0f3-4082-a4e1-9a41847fcec7" />

- ### Result 
<img width="730" height="257" alt="image" src="https://github.com/user-attachments/assets/a1e261f6-7382-415d-9e79-a716fa1811bf" />

## 3. Top 3 most popular phone brands by gender

- ### Query 
<img width="800" height="312" alt="image" src="https://github.com/user-attachments/assets/2097b1a2-7aad-4a57-a537-4cc1cb20f27a" />

- ### Result 
<img width="830" height="260" alt="image" src="https://github.com/user-attachments/assets/3f142853-9b64-4dd4-90e6-07facb46f5f7" />

## 4. Age-group analysis
- ### Query
  <img width="548" height="514" alt="image" src="https://github.com/user-attachments/assets/1312ef28-78c0-4eb3-99ed-2a113a34a63d" />
- ### Result
  <img width="772" height="217" alt="image" src="https://github.com/user-attachments/assets/9dd41f20-5290-4984-b942-1ace0e439284" />

- #### Conclusions
  - The 26–30 age group spends the most → prioritize marketing campaigns for this segment.
  - The 31–35 age group ranks second, with a preference for mid-to-premium products.
  - <21 and 21–25: lower purchasing power → offer more budget-friendly promotions/discounts.
  - 40+ : purchase less frequently → simplify the user experience and provide stronger customer support.
## 5. Top 3 phone models with the highest revenue each month
- ### Query
  <img width="616" height="350" alt="image" src="https://github.com/user-attachments/assets/25ef753d-5069-4c23-b747-62af2840c15d" />
- ### Result
<img width="819" height="308" alt="image" src="https://github.com/user-attachments/assets/2270d6bb-8558-40d5-bff9-5f553ec5405d" />

- #### Insight : Based on the results from the previous query, the business now has visibility into the best-selling phone products by month. Using this, we can analyze the key characteristics of these models for each month (e.g., features, price range, target segment) and develop similar features or complementary products/services that align with those preferences to drive additional revenue.

## 6. The flagship (top-performing) brand for the 26–30 age group
- ### Query
  <img width="888" height="313" alt="image" src="https://github.com/user-attachments/assets/e42f6456-33aa-4925-904e-2f51be054653" />
  
- ### Result
  <img width="860" height="133" alt="image" src="https://github.com/user-attachments/assets/c2d13e8f-c59f-44be-900a-10fbf3368878" />
## 7. Percentage of customers aged 26–30 who also purchase accessories/insurance
- ### Query
  <img width="827" height="333" alt="image" src="https://github.com/user-attachments/assets/6fc7385f-a96d-4a17-8a62-c3075447cc27" />
  
- ### Result
  <img width="827" height="149" alt="image" src="https://github.com/user-attachments/assets/5ad4ff1e-c458-4b54-b93e-8e104192f4b6" />

## 8. Accessories/insurance purchasing behavior by brand
- ### Query
  <img width="855" height="322" alt="image" src="https://github.com/user-attachments/assets/4f29fb42-e695-4eff-a023-a6074725ec48" />
  
- ### Result
<img width="468" height="489" alt="image" src="https://github.com/user-attachments/assets/05b09d12-64c9-4c56-a272-eff36d4780bd" />

- #### Insight  : We only observe accessory/insurance add-on purchases for Samsung, Apple (iPhone), and BlackBerry.

## 9. The age group most likely to prefer installment purchases
- ### Query
<img width="726" height="293" alt="image" src="https://github.com/user-attachments/assets/bb608077-4e23-4f84-a5f0-47a7c09386b8" />

- ### Result
<img width="761" height="92" alt="image" src="https://github.com/user-attachments/assets/206d9cc4-dd1a-4767-a693-4b5005b9f751" />

- #### Insight : Customers aged 26–30 are typically young working professionals with many essential needs but limited upfront savings, so they often prefer installment payments to better balance their finances.

## 10. Brand with the highest number of installment orders
-- P/S: The “most purchased via installments” brand will be determined by the total number of phones bought on installment plans for each brand.
- ### Query
  <img width="781" height="235" alt="image" src="https://github.com/user-attachments/assets/72e0af31-927d-4f7f-b0de-75400475fa70" />

- ### Result
  <img width="675" height="107" alt="image" src="https://github.com/user-attachments/assets/4154564b-c1dd-4e6a-8bc5-3db12042971e" />















