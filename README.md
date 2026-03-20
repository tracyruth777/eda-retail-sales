# Retail Sales Exploratory Data Analysis

## Project Overview
This project is an exploratory data analysis performed on retail sales data. The dataset used in this project is the Superstore dataset obtained from Kaggle. The goal of this project was to understand revenue performance, product category trends, regional distribution, and the impact of discounts on profitability.

## Business Questions
1. What does the data look like?
2. What is the overall sales and profit performance?
3. Which product categories and sub-categories drive the most revenue and profit?
4. How do sales vary across regions?
5. Is there a relationship between discount and profit?
6. How have sales trended over time?

## Key Findings
- The superstore achieved a 12.47% profit margin, above the retail industry average of 3-10%
- The top 3 loss-making product sub-categories of the superstore are Tables (~$17K in losses), Bookcases (~$3K in losses) and Supplies (~$1K in losses)
- There is a wide gap between the average discount rates for profitable (8%) and unprofitable (47%) sub-categories and a weak negative correlation between profit and discount, however the least profitable sub-categories did not have the highest discount rates
- Sales show consistent seasonal peaks in September and November-December and an overall upward trend from 2014-2017

## Recommendations
- Reevaluate pricing and cost management for Tables, Bookcases and Supplies which generated the least profit despite moderate sales volume, suggesting issues beyond discounting alone
- Redirect marketing efforts and business management efforts in the central and southern regions given they generated the least amounts in profit and sales across all regions
- Devise marketing strategies like seasonal promotions on months like January, February, April and June which were the months that showed the least performance in sales over the years
## Dataset
- **Source**: [Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final/code?datasetId=1940216)
- **Size**: 9,994 orders, 21 columns
- **Period**: 2014 - 2017
- **Features**: Order details, customer info, product categories, sales, profit, discount

## Tools & Libraries
- Python 3.11
- pandas, numpy, matplotlib, seaborn
- Jupyter Notebook
- Git & GitHub

## Project Structure
```
eda-retail-sales/
├── data/               
├── notebooks/          
│   └── 01_data_exploration.ipynb
├── reports/            
└── README.md           
```

## How to Run
1. Clone the repository
2. Create conda environment: `conda create -n eda-project python=3.11`
3. Activate environment: `conda activate eda-project`
4. Install dependencies: `pip install pandas numpy matplotlib seaborn jupyter`
5. Open `notebooks/01_data_exploration.ipynb`