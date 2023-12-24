# amazon_sales_data
An Amazon sales data project sourced from Kaggle was meticulously cleaned using Pandas. Employing SQL for in-depth analysis, I extracted valuable insights. The results were visualized with precision in both Power BI and Tableau, providing clear, interactive representations for comprehensive data interpretation.

Analysis done:
I loaded the CSV file into a Pandas DataFrame, checking for null values and performing data cleaning. The category column was split into 'main_category' and 'sub_category'. I dropped unnecessary columns and converted values to the correct data types. The script explored sales metrics such as total sales, average sales, and maximum discount percentage across main categories. A summary dataframe compared actual and discounted prices, visualized through bar plots. Finally, I exported cleaned data to a MySQL database using SQLAlchemy.

After connecting to SQL, I analyzed 'amazon_sales_data_pd.' I counted all entries, identified duplicate product entries, calculated total sales per main category, found the max rating count, and identified max discount percentages. Analyzing the difference between total discounted and actual prices, I showcased the most discounted product in each category using a standard query and a window function. Lastly, I determined the average rating per main category, rounding to one decimal. These SQL analyses provided comprehensive insights into sales, discounts, and product ratings.

Post SQL analysis, I seamlessly integrated the dataset into Tableau, refining data types. I introduced the 'Sales Difference' field (sum of discounted price minus actual price). Utilizing bar charts, tables, and line charts, I meticulously crafted a dynamic dashboard. This visualization tool adeptly captures nuanced data aspects, enhancing analytical comprehension. Its intuitive interface supports effective decision-making by presenting key metrics and trends in a visually appealing manner. This Tableau dashboard serves as a powerful tool for exploring, analyzing, and deriving actionable insights from the Amazon sales dataset.
