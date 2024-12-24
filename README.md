Here's a step-by-step breakdown of the initial analysis process from your notebook:

1)Importing Libraries:
Essential Python libraries such as numpy, pandas, matplotlib.pyplot, and seaborn were imported for data manipulation and visualization.

2)Loading the Dataset:
The dataset, Diwali Sales Data.csv, was loaded using pandas.read_csv with unicode_escape encoding.

3)Inspecting the Dataset:
The shape of the dataset (df.shape) was checked to determine the number of rows and columns.
A preview of the data was obtained using df.head().
Information about the dataset, such as column types and memory usage, was displayed using df.info().

4)Cleaning the Data:
Unnecessary or blank columns (Status and unnamed1) were dropped using df.drop().
Null values were identified using pd.isnull(df).sum() and removed using df.dropna().

5)Data Type Conversion:
The Amount column was explicitly converted to integer type (astype('int')).

6)Column Operations:
Verified the data type of the Amount column and displayed all column names.
Renamed the Marital_Status column to Shaadi.

7)Descriptive Statistics:
Used df.describe() to view overall statistics like count, mean, and standard deviation.
Focused on specific columns (Age, Orders, Amount) to understand their distribution.

8)Gender Analysis:
Created a bar chart to show the distribution of buyers by gender.
Analyzed total spending by gender, revealing that women have higher purchasing power.

[Note: Most buyers are female, and their purchasing power is greater than that of men.]

9)Age Group Analysis:
Plotted a bar chart showing the distribution of buyers by age group and gender.
Examined the total amount spent by each age group, identifying the 26-35 age group as the largest spending demographic.

[Note: Most buyers are females aged 26-35.]

10)State-Wise Analysis:
Identified the top 10 states by number of orders and total sales amount.
Plotted bar charts showing state-wise performance.

[Note: Uttar Pradesh, Maharashtra, and Karnataka are the top states for orders and sales.]

11)Marital Status Analysis:
Plotted the distribution of buyers by marital status and explored their spending habits by gender.
Highlighted that married women exhibit the highest purchasing power.

[Note: Married buyers, especially women, dominate spending.]



