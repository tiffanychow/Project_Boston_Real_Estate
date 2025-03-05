**Type:** Final class project for IBM's Statistics for Data Science with Python class on Coursera.

**Skills:** Data cleaning, data analysis, and data visualization.

**Programming language:** Python.

**Tools:** NumPy, pandas, Matplotlib, Seaborn, and Plotly Express in Jupyter Notebook.

**Background:** This case study examines a dataset of housing information and prices for Boston, Massachusetts as derived from the United States Census Service. The dataset includes variables such as property values and ages of owner-occupied homes, property locations, distributions of property types, distances to employment centers, and air quality.

**Goal:** To provide insight into the Boston, Massachusetts real estate market and answer the following questions regarding the community.
- How would you visualize the median value of owner-occupied homes using two different methods of plotting?
- How would you visualize the number of houses bounded and not bounded by the Charles River with two different methods of plotting? Is there a significant difference in the median value of these houses?
- Is there a difference in the median values of houses for each proportion of owner-occupied units built before 1940?
- Is there a relationship between nitric oxide concentrations and the proportion of non-retail business acres per town?
- What is the impact of an additional weighted distance to the five Boston employment centres on the median value of owner-occupied homes?

**Methods:** the dataset was cleaned, followed by preparation of appropriate visualizations and statistical tests (including a regression, correlation, t-test, and ANOVA with post hoc comparisons) to better understand the relationship between various characteristics of houses and their respective prices.

**Results:**
- The house values in this dataset had a large range ($5,000.00 to $50,000.00), with an average valuation of $22,532.81.
- However, the location of the house impacted its value. There were fewer houses that bounded the Charles River, but they were significantly more expensive than houses located farther away from the river.
- The age of a house also significantly impacted its price as older houses tended to be less valuable.
- Air quality was worse in areas with more non-retail business activity: there was a significant positive correlation between nitric oxide concentrations and the proportion of non-retail business acres per town, such that more business acres was associated with greater nitric oxide concentrations.
- The distance from housing to employment areas was also a consideration for price. There was a significant positive relationship between distance to the Boston employment centers and housing values where greater distances was related to higher house prices.
