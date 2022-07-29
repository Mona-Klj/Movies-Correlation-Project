## Movies-Correlation-Project

Considered an exploritory in Movies dataset from Kaggle in this repository to find the correlation with gross values vs other variables.

Dataset is available as a CSV file. 

## Data Preprocessing :

1- Loaded essential libraries

2- Lodead data from a CSV file

3- Cheked for missing data

4- Dropped duplicates if there's one

5- Dropped any rows with null values

6- Changed data type of numeric columns to int64

7- Dropped the rows which the values are in the 'released' column, that doesn't have a full date

8- Converted 'released' to datetime type

9- Reordered columns and sorted by gross values

## The question was "what is most correlated to gross"

My guess:

* Frist Thought: Budget high correlation
* Company high correlation

## Data Visualization :

1- created Scatter plot with budget vs gross

2- Plotted the budget vs Gross uning Seaborn

3- looked at correlations

## There is High correlation between Budget and Gross and I was right

4- Changeed every objects Columns to category type

5- Plotted Haetmap for all columns

6- created corr table

## votes and budget have the highest correlation to gross earnings
## company has low correlation
