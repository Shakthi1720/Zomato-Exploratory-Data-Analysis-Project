# Zomato Exploratory Data Analysis (EDA) Project

## Project Overview
This project explores a Zomato restaurant dataset using Python to understand restaurant categories, customer votes, ratings, online ordering, table booking, and approximate dining costs.

The analysis uses Pandas for data preparation and summarization, and Matplotlib and Seaborn for visualizing patterns and insights.

## Objectives
- Understand the dataset structure and summary statistics.
- Clean and prepare restaurant ratings and column names.
- Identify missing values and duplicate records.
- Compare restaurant categories based on votes, ratings, restaurant counts, and estimated costs.
- Explore the relationship between ratings, customer votes, and online ordering.

## Tools & Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset
The project uses a supplied CSV dataset containing **148 restaurant records and 7 columns**.

| Column | Description |
|---|---|
| Restaurant Name | Restaurant name |
| Online_Order | Online ordering availability |
| Book_Table | Table booking availability |
| Rate | Restaurant rating |
| Votes | Number of customer votes |
| Approx_Cost(For Two People) | Approximate cost for two people |
| Listed_In(Type) | Restaurant category |

## Data Cleaning
The following data preparation steps were performed:

- Converted restaurant ratings from text format (e.g., `4.1/5`) into numeric values.
- Standardized column names to lowercase.
- Renamed the approximate cost column to `approx_cost`.
- Checked for missing values and duplicate records.

**Data quality results:** No missing values or fully duplicated rows were found.

## Exploratory Data Analysis
The project investigates the following questions:

1. How many customer votes has each restaurant type received?
2. How many restaurants offer table booking?
3. Which five restaurants have the highest number of votes?
4. Is there a relationship between restaurant ratings and customer votes?
5. What is the average rating for each restaurant type?
6. Which restaurant type is most common in the dataset?
7. What ratings do restaurants most commonly receive?
8. Which restaurant type has the highest average cost for two people?
9. Do restaurants offering online ordering have higher ratings?
10. Which restaurant types have more records without online ordering?

## Key Findings
- **Most common restaurant type:** Dining, accounting for 110 records (74.3%).
- **Highest total votes:** Dining restaurants, with 20,363 votes.
- **Table booking:** Available in 8 records (5.4%); unavailable in 140 records (94.6%).
- **Most voted restaurant:** Empire Restaurant, with 4,884 votes, followed by Meghana Foods with 4,401 votes.
- **Rating and votes:** Moderate positive correlation of approximately 0.49.
- **Highest average rating:** Other category, with approximately 3.91 out of 5.
- **Overall rating:** Mean of 3.63, median of 3.7, and mode of 3.8.
- **Highest average cost for two:** Buffet, at approximately 671.43.
- **Online ordering:** Restaurants offering online ordering have an average rating of 3.86, compared with 3.49 for those without it.
- **Dining without online ordering:** 77 records are marked No.

## Conclusion
The analysis identifies Dining as the most common restaurant category and the category with the highest total customer votes. Buffet restaurants have the highest average approximate cost for two people, while the Other category has the highest average rating.

Table booking is uncommon in the dataset, and restaurants offering online ordering have higher average ratings in this sample.

These findings describe the 148 supplied restaurant records and should not be generalized to all Zomato restaurants.

---

# Author
Shakthi Sharma
