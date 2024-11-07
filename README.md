# World Bank International Debt Analysis using SQL
This project explores the World Bank's international debt data, focusing on the debt owed by developing countries. The analysis utilizes SQL queries to extract insights and answer key questions about the data.

### Project Description
The World Bank provides debt to developing countries to support infrastructure development and other initiatives. This project analyzes a dataset containing information about the amount of debt (in USD) owed by these countries across various categories.

### Key Questions Addressed:

* What is the total debt owed by all countries in the dataset?
* Which country has the highest amount of debt?
* What is the average debt owed by countries across different debt indicators?
* What are the most common debt indicators?

Analysis Steps
The analysis proceeds through several stages:

1. Connecting to the Database: The first step connects to the international_debt database where the debt data resides.

2. Initial Exploration: The initial exploration retrieves the first ten rows of data to get a basic understanding of the columns and data format.

3. Number of Unique Countries: This section counts the unique number of countries in the dataset, as the raw data might have duplicate entries due to multiple debt indicators for each country.

4. Distinct Debt Indicators: We identify the different debt indicators present in the data, which help categorize the purpose of the debt.

5. Total Debt Owed: The total amount of debt owed by all countries combined is calculated.

6. Country with Highest Debt: This section identifies the country with the highest overall debt burden.

7. Average Debt per Indicator: We calculate the average debt owed by countries across various debt indicators to understand the distribution of debt across categories.

8. Highest Principal Repayment: The indicator representing the highest average debt is analyzed further.

9. Most Common Debt Indicator: The most frequent debt indicator used by countries is identified.

10. Other Debt Issues: The analysis explores the maximum debt owed by individual countries, suggesting potential economic issues beyond long-term debt.

### Conclusion
This project provides a glimpse into the international debt landscape for developing countries. We extract key information about total debt, average debt by indicator, and debt distribution across countries. By analyzing the data, we gain valuable insights into potential economic challenges faced by these nations.

**Disclaimer**
Note: This analysis assumes the provided code snippets using %%sql magic commands are functional representations of the actual SQL queries used.
