# Power-BI-Assignments-sneha-mohan
Power BI Assignments containing data analysis,data cleanig,and visualization
#### Import Data
Imported the required datasets into Power BI using Excel and CSV files. The datasets included List of Orders, Order Details, and Sales Target. Used the Get Data option to connect and import the data into Power BI. Opened Power Query Editor to check the tables and prepare the data for further analysis.
#### Data Transformation
Performed data cleaning and transformation using Power Query Editor in Power BI. First, selected the List of Orders table and used the Keep Rows option to retain only the first 500 rows. Changed the Order Date column to Date data type and converted Amount and Target columns to Fixed Decimal Number. Used the Format option and selected Capitalize Each Word to convert Customer Name into Proper Case. Selected the City and State columns and used Merge Columns with a comma separator to create a new Location column. Then, used the Custom Column option to calculate Profit Margin by dividing Profit by Amount and formatted it as a percentage. Finally, used the Conditional Column option to create a Profit Status column and classified the records as Loss, Break Even, or Profit based on the Profit values.
#### Merging Data (Joins)
Merged the List of Orders and Order Details tables using the Merge Queries as New option in Power Query Editor. Selected the Order ID column from both tables as the matching column and used Left Outer Join. Expanded the required columns and renamed the new table as Order Database.
#### Handling Missing Data & Duplicate Data
Checked all columns in the tables using the filter dropdown to identify missing values. No null or blank values were found in the data. Then, checked for duplicate rows using the Remove Duplicates option under the Home tab in Power Query Editor. Removed exact duplicate rows to maintain data accuracy and consistency.
#### Sorting and Filtering Data
Applied sorting and filtering techniques using Power Query Editor. First, selected the Order Date column in the List of Orders table and used the Sort Descending option to display the most recent orders first. Then, used the filter option in the State column and selected only Tamil Nadu to focus on orders from that state for regional analysis.
#### Grouping and Aggregating Data
Performed grouping and aggregation using Power Query Editor. First, duplicated the Order Details table and created three summary tables using the Group By option. Grouped the data by Order ID to calculate Total Amount using Sum, by Category to calculate Average Profit using Average, and by Sub-Category to calculate Total Amount using Sum. Next, duplicated the Sales Target table, extracted the Month Name from the Order Date column, and grouped the data by Month Name to calculate the Total Target using Sum
#### Data Modeling
Created relationships between tables using the Manage Relationships option in Power BI. First, established a relationship between the List of Orders and Order Details tables using the Order ID column with a One-to-Many relationship. Next, created a relationship between the Order Details and Sales Target tables using the Category column with a Many-to-Many relationship and Both cross-filter direction. Ensured that both relationships were active.

