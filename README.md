# Housing

# Housing Data Analysis

This project involves performing data analysis on housing data using Python and the pandas library.

## Dataset

The dataset used is `Housing+Data.csv`. It contains information about housing, including dates, area, average price, code, houses sold, and crime data.

## Project Goals

The primary goals of this project are to analyze the housing dataset using pandas. Specific operations include:

1.  Converting the 'Date' column to datetime format.
   
2.  Adding new columns for 'year' and 'month'.
   
3.  Removing the 'year' and 'month' columns.
   
4.  Finding records where the number of crimes is 0.
   
5.  Determining the maximum and minimum average prices per year for England.
   
6.  Determining the maximum and minimum number of crimes recorded per area.
   
7.  Showing the total count of records for each area where the average price is less than 100000.

## Libraries Used

* pandas
* seaborn
* matplotlib.pyplot

## Code Description

1.  **Import pandas:** The pandas library is imported for data manipulation and analysis.
   
2.  **Load the dataset:** The dataset is loaded into a pandas DataFrame.
   
3.  **Data Exploration:**
   * The code calculates the count of non-null values for each column.
   * The code calculates the sum of null values for each column.
   * A heatmap is generated to visualize null values.
4.  **Convert 'Date' to datetime:** The 'Date' column is converted to datetime format.
   
5.  **Add 'year' and 'month' columns:** New columns 'year' and 'month' are added to the DataFrame, extracted from the 'Date' column.
   
6.  **Remove 'year' and 'month' columns:** The 'year' and 'month' columns are removed from the DataFrame.
   
7.  **Analyze crime data:**
   * Records where the number of crimes is 0 are identified.
   * The maximum and minimum number of crimes per area are calculated.
8.  **Analyze average prices:**
   * The maximum and minimum average prices per year for England are calculated.
   * The total count of records for each area with an average price less than 100000 is determined.

## Results

* The 'Date' column was successfully converted to datetime format.
   
* 'Year' and 'month' columns were added and removed.
   
* Analysis of crime data and average prices was performed as described in the project goals.

## Code Snippets

### Load Dataset

```python
import pandas as pd
data = pd.read_csv("C:/Users/gvrk1/Downloads/Housing+Data.csv")
