# S&P 500 Data Analysis
The Standard and Poor's 500, or simply the S&P 500, is a stock market index tracking the stock performance of 500 of the largest companies listed on stock exchanges in the United States.

### Table of Contents

- [Project Overview](#project-overview)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Limitations](#limitations)
- [References](#references)


### Project Overview
This data analysis project aims to provide insights into the revenue and market cap performance of S&P 500 companies. To organize the dataset and utilize it in a better way, I have grouped multiple companies to form industrial sectors. By analyzing various aspects of such industries, we seek to identify trends and gain a deeper understanding of the growth in different industrial sectors in different parts of the world. 


### Data Source
The primary dataset used for this analysis was downloaded from Kaggle.com and there are three different files- sp500_companies.csv, sp500_index.csv and sp500_stocks.csv containing detailed information about each industrial sector which form the overall larger group classified as S&P 500.


### Tools Used
- Microsoft Excel for Data Cleaning
- Tableau for Data Analysis and Creating Reports


### Data Cleaning/Preparation
In the initial data preparation phase we performed the following tasks:
- Data Loading and Inspection
- Handling missing values
- Data cleaning and formatting

### Exploratory Data Analysis.
EDA involved exploring the S&P500 Companies data to answer key questions. We will try to answer a few of the key questions below that were created to explore this project's data set. With every question, dashboard images have been included along with the analysis. Please click to explore and interact with the dashboard using the Tableau link to this visualization: https://public.tableau.com/app/profile/anam.vakil/viz/SPFinanceAnalysisGithub/FinalDashboard?publish=yes

1. What are the Market Cap and Current Price statistics of the top 10 industries in the S&P 500?

![MarketCap_and_CurrentPrice](https://github.com/anamvakil/S-P500-Data-Analysis/assets/160653463/73717d05-3504-4af3-bde4-fcbec7aa3e30)

2. What is the difference between the top 10 industries when comparing Market Cap and Revenue Growth?

![MarketCap_vs_RevenueGrowth](https://github.com/anamvakil/S-P500-Data-Analysis/assets/160653463/375ef83e-3af8-4f13-b366-dfe43f7450c1)

## Analysis
- When we analyze the first image for question 1 above, we can see a horizontal bar graph at the top representing the current market cap and the current price per share of each of the top 10 industries in the S&P 500.
- For the second question, the two tables in the image help us showcase the differences between the top 10 industries based on Market Cap and Revenue growth. To portray the significance of filters and how they add value to the overall data analysis, it can be observed that the list of industries changes as soon as we filter out 2 different measures namely the Sum of Market Cap and the Sum of Revenue Growth.
- As we go ahead and look at the top 10 industries by revenue growth table closely, we see that there are negative values in the table. It becomes imperative to address these values and what they mean to the top 10 industries. Any particular industry with a negative value may seem to have a negative revenue growth percentage, however, such industries still make the top 10 ranks because of their overall contribution in other countries. Hence, despite having a negative value such an industry is still a valid entry in the top 10 category.

3. What is the correlation between the number of full-time employees and a company's revenue growth?

![Map and Tree map](https://github.com/anamvakil/S-P500-Data-Analysis/assets/160653463/377fdae6-4840-468e-95d7-494c8bdae87a)

## Analysis:
- The above graph represents a Map and a Tree Map showcasing how the number of full-time employees affects the revenue growth percentage in different industrial sectors
- It can be easily inferred that in most cases the revenue growth percentage decreases as the number of full-time employees decreases. However, there are certain exceptions to this rule and these can be observed in the software and hardware industries
- Thus, by using this data analytics approach, we can gain insights into industry patterns and existing exceptions for a particular industry in a country

4. Which years had the highest opening and closing values?

![Question 4](https://github.com/anamvakil/S-P500-Data-Analysis/assets/160653463/4a841000-9573-466e-a1e8-d202c2c35011)

 ## Analysis.
 - The above interactive dashboard represents the Opening and Closing Values of Industries over the last decade. This helps us in answering the fourth question.
 - The usage of a dual axis in the bar graph helps us compare the two datasets easily and see any correlations or trends that may exist between them.
 - In the analysis process, I saw a sharp decline in the graph which raised a question in my mind: Why has this sharp decline happened? Further observation reveals that the year of this decline shown in the graph is 2024. Since 2024 is the ongoing year, we do not have complete data for the same. Hence we do not see the title in the axis for that graph and thus we cannot conclude whether the trend is upward or downward.

 5. Which year and quarter were the most profitable over the last decade?

![Quarterly Profits Analysis (1)](https://github.com/user-attachments/assets/589a3319-6f62-4ce9-8e19-2435732f7b07)

  ## Analysis
  - This analysis highlights one of the issues which many of us face i.e. you don’t have the data you need or you don’t have sufficient data.
  - As per Google's Data Analytics course, in such a scenario, we have to adjust your analysis to align with the data you already have.
  - To showcase the importance of such an adjustment I have done the analysis using both scenarios as you can see in the above image.
  - The first graph in the image shows the analysis made for the years 2019-2024 where we see that due to the incomplete data for the year 2024, there is a steep decline despite the overall trend being positive and going upward.
  - Whereas, in the second graph in the dashboard, I have used the filter to only show the analysis from 2019-2023 as it has complete data for 2023. This approach gives us a more stable graph and also results in a completely different conclusion from our analysis of the first graph.
  - This showcases the importance of factors like incomplete data or insufficient data in a particular dataset if we want to come to an accurate conclusion using our data analysis.

    
  ## Limitations:
  - The Group Function has been used to group different industries into industrial sectors.
  - The Hierarchy Function has been used to create a hierarchy of countries for a better understanding of the data.
  - While learning from [Process Data from Dirty to Clean](https://www.coursera.org/learn/process-data/home/module/1), I have learnt that if the dataset is too large to survey then one can survey a representative sample of the dataset. To implement this method I used various filters to filter out the top 10 industries wherever necessary and then performed my analysis.

 ### Conclusion:
 ---
 All the above-given dashboards present the data in different types of charts and graphs. This helps us to easily and quantitatively study various aspects related to the performance of the S&P 500 industries in the past. Finally, these dashboards also allow us to analyze how different aspects of these industries had an impact on their overall rise or decline as a part of the S&P 500.

 ### References:
 - [Tableau Certified Data Analyst: Top Exam Prep Course by Lukas Halim](https://www.udemy.com/share/101Wus3@cLobZ0XBRNKwQjuZbMQquN4BG6LhCksrBekTXv271XYkDmR6A2ftFbSGLQBij6bwAA==/)
 - [Kaggle.](https://www.kaggle.com/)
 - [Ask Questions to Make Data-Driven Decisions](https://www.coursera.org/learn/ask-questions-make-decisions)
 - [Process Data from Dirty to Clean](https://www.coursera.org/learn/process-data/home/module/1)

