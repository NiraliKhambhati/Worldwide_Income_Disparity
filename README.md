
## Global Income Inequlity Analysis
This project analyzes global income inequlity trends using data from various countries over multiple years. The analysis focuses on key metrics such as the Gini Index, income shares of top and bottom 10%, and income groups across different nations. 

### Project Overview
The project aims to :
- Examine income inequality patterns across countries and years.
- Analyze the relationship between various economic indicators.
- Provide insights into global income distribution trends.

### Data Description
The data includes the following key variables:
- Country
- Year
- Population
- Gini Index
- Average Income (USD)
- Top 10% Income Share (%)
- Bottom 10% Income Share (%)
- Income Group

### Key Finding
- The average Gini Index across all observations is 0.426, indicating a moderate level of income inequility globally.
- There is significant variation in income inequiality metrics inequality metrics across countries and years.
- The average income share of the top 10% is 40.2%, while the bottom 10% only accounts for 3% of income on average.
- Income groups very widely, with some countries experiencing shifts between income categories over time.

### Methodology
The analysis employs descriptive statistics and regression analysis to explore relationships between variables. A linear regression model was used to examine the impact of top and bottom income shares on the Gini Index.

### Code Structure
The project is implemented in Python using Jupyter Notebooks. Key librarires used include:
- Pandas for Data manipulation
- Matplotlib and Seaborn for data visulization
- Statsmodels for regression analysis

### Installation and Usage
To run this project:
1. Clone the repository
2. Install required dependancies: pip install -r requirements.txt
3. Open and run the Jupyter Notebook: jupyter notebook Global-Income-Inequity-3.ipynb

### Contributing
Contributions to improve the analysis or extend the project are welcome. Please submit a pull request with your proposed changes.

### Licnese
This project is open-source and available under the MIT License.
