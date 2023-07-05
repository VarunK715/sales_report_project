Sales Report Data Analyst Project

=> Downloaded datasets from codebasics youtube channel and imported into My-SQL workbench.
=> After importing data into workbench, did data viewed and manipulated data such as updating or removing blank rows.
=>Next step is connecting My-SQL workbench to Power BI, inorder to build Report.
=>loaded data from workbench to power bi and using Power Query, i did data transformaion and clening .
=?Finaly step is to build dashboard. beofre that i created calculated columns and Measures.

From this project i learned how to load data to Power BI and clean,transform data, also use of calculated columns and measure, DAX formula.

==========================

1. Using DAX Formula to create norm_amount column 

`= Table.AddColumn(#"Filtered Rows", "norm_amount", each if [currency] = "USD" or [currency] ="USD#(cr)" then [sales_amount]*75 else [sales_amount], type any)`



