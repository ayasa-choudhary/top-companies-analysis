This project analyzes a dataset containing information about top companies, including their rank, name, industry, revenue, revenue growth, and number of employees. The goal is to explore the relationships between various metrics and visualize insights using Python libraries like Matplotlib and Seaborn.

Key Features of the Analysis

1. Exploratory Data Analysis (EDA)
	•	The dataset was explored to identify patterns, trends, and relationships between variables.
	•	A variety of visualizations were created using Matplotlib and Seaborn.

Visualizations and Techniques Used

1. Pair Plot
	•	Created using sns.pairplot to visualize pairwise relationships between numerical columns like revenue, revenue growth, and employees.
	•	Helps in identifying trends, correlations, and outliers in the data.

2. Bar Plot
	•	Generated using plt.bar to compare industries based on total revenue or average revenue growth.
	•	The industries were ranked visually to understand which sectors dominate in terms of financial performance.

3. Scatter Plot
	•	Used sns.scatterplot to show relationships between revenue and revenue growth or revenue and employees.
	•	Color-coded points by industry to highlight variations across sectors.

4. Figure Customization
	•	plt.figure was utilized to set up custom figures for plots, ensuring clear and professional presentation of visuals.

Dataset Columns

The dataset contains the following columns:
	1.	Rank: The ranking of the company among the top companies.
	2.	Name: The name of the company.
	3.	Industry: The sector or industry the company operates in.
	4.	Revenue: The total revenue of the company.
	5.	Revenue Growth: Percentage growth in revenue year-over-year.
	6.	Employees: Total number of employees in the company.

Insights

	•	Identified industries with the highest revenue growth and total revenue.
	•	Explored correlations between company size (employees) and revenue.
	•	Visualized how different industries cluster based on financial and workforce metrics.
