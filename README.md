# Instacart-Python-Analysis
### SUMMARY: 
A demo project using Jupyter Notebooks to clean, merge, analyze and finally visualize publicly available data from Instacart and fictitious customer data from CareerFoundry.

### OBJECTIVES
•	Clean and merge four data sets: order data, product data, department data, and customer data.

•	Analyze the data to answer questions from marketing and sales teams (for example, busiest times of day, highest grossing days of the week, most popular groups of products, most loyal customers, etc.)

•	Analyze the data to discover differences in users’ ordering habits based various characteristics (such as region, gender, income, loyalty status, etc.)

•	Create customer profiles based on combinations of variables and analyze how their ordering behaviors may differ (for instance, parents of babies, pet owners, senior citizens, etc.)

### DATA
Order and product information borrowed with permission from “The Instacart Online Grocery Shopping Dataset 2017.” Accessed on 3/6/2023 via https://www.instacart.com/datasets/grocery-shopping-2017

Fictitious customer information and fictitious prices for products created by CareerFoundry for the purposes of this project: https://s3.amazonaws.com/coach-courses-us/public/courses/data-immersion/A4/A4_Data_Assets/customers.zip 


### TOOLS
*Language:* Python

*Libraries:* Pandas, NumPy, Matplotlib and Seaborn

*Software:* Jupyter Notebooks and Excel


### SKILLS DEMONSTRATED
•	**Cleaning data:** removed duplicates, found and resolved missing values, addressed mixed (or incorrect) data types, checked for outliers/errors and fixed them.

•	**Merging data:** selected and prepared data for merge (including transposing data when needed), confirmed merge was successful afterwards, and exported final merge as a pickle file.

•	**Exploratory analysis of data:** explored basic descriptive statistics (max/min, quartiles, mean, standard deviation) for each variable as well as using histograms, scatterplots, and bar and line charts to explore the distributions of data to identify areas worth more in-depth analysis.

•	**Deriving new variables:** grouped data by user, order, and department to allow exploration and analysis at each level; used aggregated data to create flags about user ordering habits (such as ‘new customer’, ‘frequent shopper’, etc.) and demographic info (such as ‘parent of a baby’ or ‘pet owner’); confirmed the new data created via crosstabs and value_counts. 

•	**Visualizing data:** used Matplotlib and Seaborn to create histograms, line charts, pie charts, and bar charts (vertical/horizontal, stacked, and 100% stacked).  Customized colors, legends, labels and annotations for clarity and visual consistency. 

•	**Reporting results:** provided an Excel file that vividly explained the answers to all questions from sales/marketing as well as documenting the data population flow, consistency checks, data wrangling, and column derivations.
