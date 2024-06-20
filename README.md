# Project Documentation: *Data Analysis for 2020 Tokyo Olympics Games*

## Project Title - Data Analysis for 2020 Tokyo Olympics Games

## Project Overview
The focus of this project is on analyzing the performance of countries in the 2020 Tokyo Olympics, which had 92 participating countries competing for medals in three categories: Gold, Silver, and Bronze. The analysis aims to identify countries with the highest and lowest medal counts, determine the number of countries that participated but did not win any medals, and predict factors contributing to the success of top-performing countries like the USA, Great Britain, Japan, and People's Republic of China. The goal is to derive meaningful insights that can help other countries improve their performance in future Olympics.

## Data Source

A CSV file containing data on the 2020 Tokyo Olympics.

## Tools Used

- Jupyter Notebook
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
  
## Data Cleaning

- Data cleaning was performed using Jupyter Notebook and various Python libraries
- Checked for null values and handled them appropriately.
- Normalized data types for consistency.
- Used box plots to identify and confirm the absence of outliers.
- Dropped non-numeric columns that could negatively affect the machine learning model.

## Exploratory Data Analysis (EDA)

The dataset comprised 93 rows and 6 columns, with the following statistical summary:

- Count: 93
- Mean: 3.655914
- Standard Deviation (std): 7.022471
- Minimum (min): varied based on the column
- Maximum (max): Varied based on the column
- 25%, 50%, and 75% Interquartile Range (IQR): Provided insights into the distribution of the data.

## Results and Findings:

- The United States won the most medals overall, while Tunisia won the fewest.
- Sixteen countries did not win any medals.
- Detailed breakdown of medals won by each country in each category (Gold, Silver, Bronze).

## Screen shots of data visualizations

![Screenshot (47)](https://github.com/Ezeco/Tokyo_Olympic_2021_Data_Analysis/assets/125317057/ca719c16-86e4-4e88-89fd-c3f873198c8a)

![Screenshot (48)](https://github.com/Ezeco/Tokyo_Olympic_2021_Data_Analysis/assets/125317057/4fd6330f-4129-40a6-bc35-40a0baf4720a)


## Recommendations:
Based on our findings, several factors contributed to the success of top-performing countries:

- Better preparation and training
- Strong team spirit
- High-quality training facilities and equipment
- Commitment and dedication of athletes
- Sufficient funding and resources
  
### To improve performance in future Olympics, countries should:

- Provide adequate support and funding for their athletes.
- Invest in high-quality training facilities and equipment.
- Foster a strong team spirit and commitment.
- Implement comprehensive preparation and training programs.

## Limitations

- The dataset is relatively small, with only 93 rows and limited variables.
- The data lacks depth and quality for a more comprehensive analysis.
- The analysis may not account for all factors affecting performance, such as political, economic, or cultural influences.

## Data Modeling

The following steps were taken for data modeling using linear regression:

- Imported libraries: LinearRegression, train_test_split.
- Defined and separated the variables into X (features) and y (target).
- Split the data into training and testing sets.
- Created a linear regression model.
- Checked the normality of residuals and evaluated the Ordinary Least Squares (OLS) regression results.
- Assessed the regression score and model accuracy, which was found to be 100%.
  
![Screenshot (49)](https://github.com/Ezeco/Tokyo_Olympic_2021_Data_Analysis/assets/125317057/125e8a53-dce1-4461-a62e-be512f010c0b)


## References

Kaggle: Dataset for 2020 Tokyo Olympics [(https://www.kaggle.com/)]

Python Documentation [(https://docs.python.org/3/)]

Pandas Documentation [(https://pandas.pydata.org/docs/)]

NumPy Documentation [(https://numpy.org/doc/)]

Matplotlib Documentation [(https://matplotlib.org/stable/contents.html)]

Seaborn Documentation [(https://seaborn.pydata.org/)]

Scikit-learn Documentation [(https://scikit-learn.org/stable/)]


