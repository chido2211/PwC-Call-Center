# PwC-Call-Center
Power BI Dashboard 
### Dashboard Link :https://t3hx5-my.sharepoint.com/:u:/g/personal/chido_t3hx5_onmicrosoft_com/EW-zWj59fpJDvePDV7Tk7t0BCXUOV4aIz_HK2Q4XzfBcYw?e=2wKEKc

## Problem Statement
The Telecom Marketing Dashboard aims to provide insights into customer satisfaction and operational performance for a major telecom company. By analyzing various KPIs and metrics, the dashboard assists the company in understanding customer preferences and areas for improvement in their services.

## Data Visualization (Dashboard) :
![Screenshot_1-4-2024_161642_](https://github.com/chido2211/PwC-Call-Center/assets/149630627/a4452fbd-a21d-4ed9-a032-9a24ea152ed8)

## Insights

### 1. Average Speed of Answer (SOA)
- The average speed of answer across all calls is 67.52 seconds.
- This metric indicates the average time it takes for calls to be answered by agents.

### 2. Number of Calls per Month
- Monthly call volumes vary, with January having the highest call volume (1772) and February the lowest (1616).
- The proportion of answered calls compared to unanswered calls is relatively consistent across months, with a high percentage of calls being answered.

### 3. Answered and Resolved Calls
- A significant majority of calls (81.08%) are answered, indicating a good response rate from the telecom company.
- Similarly, a large portion of calls (72.92%) are resolved successfully.

### 4. Average Satisfaction Rating
- The average satisfaction rating across all calls is 3.4, falling short of the target of 4.5.
- This suggests there is room for improvement in meeting customer expectations.



### Measures Used (DAX Formula)

- **Answered**: CALCULATE(COUNT(Sheet1[Call Id]),FILTER(Sheet1, Sheet1[Answered (Y/N)]="Y"))
- **Resolved (Y)**: CALCULATE(COUNT(Sheet1[Call Id]),FILTER(Sheet1,Sheet1[Resolved]="Y"))
