# About the Project 

- This project focused on performing **data exploration in Python** with the supplementation of **matplotlib** and **seaborn** to visualise patterns and trends.
- The dataset used was provided by [Kaggle](https://www.kaggle.com/datasets/russellyates88/suicide-rates-overview-1985-to-2016).

# Methodology 

Before conducting the project the dataset was studied to understand the nature of the dataset. Areas of interests were then noted providing a guideline for the direction of the analysis.  The insights and their corresponding methodologies are discussed below.

### Which countries had the highest total suicide count from 1985 to 2016?
- Groupby and aggregations to group data by country and sum suicide count.
- Seaborn barplot (horizontal orientation) to visualise trend.

### Do more males or females commit suicide?
- Groupby and aggregations to group data by gender and sum the suicide count.
- Matplotlib to visualise findings. 

### How are annual suicide rates changing over time?
- Groupby and aggregations similar to above.
- **shift()** method to compare current row with previous enabling the calculation of percentage change.
- Matplotlib subplots supplemented with seaborn line plots to analyse percent changes in annual suicide amounts for male, female and totality. 

### Which age bracket featured the greatest number of suicides?
- Groupby and aggregations.
- Matplotlib bar plot.

### Can any correlation be deduced between GDP and total number of suicides.
- Groupby and aggregations.
- **agg()** method to perform multiple aggregations supplemented with **numpy** aggregation methods.
- Matplot lib pie chart to visualise the what share of GDP the countries with the Top 10 suicide counts has compared to the GDP of all the countries in the dataset. 

# Conclusions
1) The top 3 countries with the highest suicide counts were Russia, US and Japan. To view the top 10 please see the workbook.
2) Suicide totals for males were 3.32 times greater than that of females.
3) Counts of suicide were increasing from 1985-2000. However, from 2000-2016 exhibited a downward trend.
4) Suicide was greatest in the 35-45 age bracket.
5) A positive correlation existed between GDP and suicide count. 
