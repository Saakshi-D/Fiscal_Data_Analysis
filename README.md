# **Financial Data Analysis**
This project analyzes financial data from various segments, countries, and products. It includes data cleaning, visualization, statistical analysis, and linear regression to understand different financial aspects such as total gross sales, sales trends, profit margins, and the impact of discounts.

## **About the Dataset**
[Dataset Link](https://www.kaggle.com/datasets/atharvaarya25/financials)

The dataset used in this project contains the following columns:
* Segment
* Country
* Product
* Discount Band
* Units Sold
* Manufacturing Price
* Sale Price
* Gross Sales
* Discounts
* Sales
* COGS  (Cost of Goods Sold) 
* Profit
* Date
* Month Number
* Month Name
* Year

## **Steps and Analysis**
### **1. Data Cleaning**

Removed leading and trailing spaces from column names.
Converted Date column to datetime format.
Removed dollar signs, commas, and other unwanted characters from numeric columns.
Converted necessary columns to appropriate data types.

### **2. Exploratory Data Analysis**
Total Gross Sales Calculation:
Calculated total gross sales for each segment.
Visualized segment-wise total gross sales using a bar plot.

Average Sales Price Calculation:
Determined the segment with the highest average gross sales.
The segment with the highest average gross sales is Small Business.

Country-wise Sales Calculation:
Calculated total sales for each country.
Visualized country-wise sales using a bar plot.

Impact of Discounts on Gross Sales:
Compared average gross sales with and without discounts.
Performed a two-sample t-test to check the statistical significance of the difference.

The difference in average sales with and without discounts is not statistically significant (p-value: 0.3168).

### **3. Time Series Analysis**
Sales Trends Over Time:
Grouped data by year and month to understand sales trends.
Visualized sales trends over the years and months.


### **4. Profit Margin Analysis**
Profit Margin Calculation:
Calculated the profit margin for each row.
Visualized the distribution of profit margins using a histogram and violin plot.


### **5. Linear Regression Analysis**
Discount Band vs. Profit:
Performed linear regression to analyze the relationship between discount levels and profit.
The relationship between discount band and profit was found to be negligible.

Product Price vs. Units Sold:
Analyzed the relationship between product price and units sold using simple linear regression.

## **Results**
The segment with the highest total gross sales is Government.
The country with the highest total sales is United States of America.
The difference in average sales with and without discounts is not statistically significant.
Small Business segment has the highest average gross sales.
No significant linear relationship between discount band and profit was found.

## **Detailed Key Findings**
### **1. Segment Performance:**

The Government segment has the highest total gross sales, indicating strong performance and high revenue generation potential within this sector.
Small Business segment exhibits the highest average gross sales per transaction, suggesting a high-value market with significant individual sales.

### **2. Geographical Insights:**

The United States of America leads in total sales, making it a critical market for our operations.
Other countries also contribute significantly, and a deeper dive into regional strategies might reveal opportunities for growth

### **3. Discount Impact:**

Analysis reveals that the difference in average sales with and without discounts is not statistically significant (p-value: 0.3168). This suggests that offering discounts does not have a considerable impact on gross sales volumes.
This finding can help refine discount strategies, potentially reducing unnecessary price reductions and protecting profit margins.
### **4. Sales Trends:**

There are discernible trends in sales over years and months, with certain periods showing higher sales volumes.
Seasonal patterns can inform inventory management and marketing campaigns to optimize sales during peak times.
### **5. Profit Margins:**

Profit margin analysis indicates variability across segments, with some showing higher margins than others.
Focused efforts to improve margins in lower-performing segments could enhance overall profitability.
### **6. Product Pricing and Sales Volume:**

Linear regression analysis shows negligible impact of discount bands on profit, reinforcing the finding on discounts.
There is a relationship between product price and units sold, indicating pricing strategies need to be carefully balanced to maximize both volume and revenue.
Recommendations
### **7. Segment Strategy:**

Invest in strengthening relationships and offerings within the Government segment to capitalize on its high revenue potential.
Explore opportunities to expand in the Small Business segment, leveraging its high average sales per transaction.
Market Focus:

Continue to prioritize the United States of America while exploring untapped potential in other significant markets.
Tailor regional strategies to leverage specific market conditions and consumer behavior.
### **8. Discount Policies:**

Reevaluate current discount strategies, considering the minimal impact on sales volumes. Focus on targeted discounts that drive customer loyalty without eroding profit margins.
Experiment with value-added promotions rather than price cuts to enhance perceived value.
Seasonal Planning:

Utilize identified sales trends to plan inventory and marketing campaigns. Focus on peak sales periods to maximize revenue.
Develop off-season strategies to maintain steady sales flow throughout the year.
### **9. Profit Optimization:**

Conduct detailed margin analysis across all segments to identify specific areas for cost reduction and efficiency improvement.
Implement best practices from high-margin segments across the board.
Pricing Strategies:

Fine-tune pricing strategies to balance between competitive pricing and maintaining healthy profit margins.
Consider dynamic pricing models to respond to market demand and competitor actions in real-time.

## **Requirements:**
Python 3.x

Libraries: numpy, pandas, matplotlib, seaborn, sklearn, scipy
