**Project Overview: Life Expectancy and Global Health Analysis**

_Objective_

This project focuses on cleaning, analyzing, and exploring global life expectancy data, GDP metrics, and mortality statistics to uncover trends and correlations that provide insights into global health and economic conditions. Using SQL queries and structured analysis, the project addresses key questions about life expectancy changes, economic factors, and mortality patterns across countries and over time.


_Life Expectancy Trends by Country_
- Calculated the minimum, maximum, and difference in life expectancy for each country.
- Identified countries with the largest increases in life expectancy over time.
- Filtered out invalid values (e.g., zero life expectancy) to ensure accurate insights.
- Ranked countries by the magnitude of life expectancy improvement.
- Global Life Expectancy Over Time

_Computed the global average life expectancy for each year._
- Tracked changes in average life expectancy, providing a clear view of global health trends.
- Ensured data quality by removing zero or invalid values.
- Correlation Between GDP and Life Expectancy

_Calculated the average GDP (in millions) and average life expectancy for each country._
- Highlighted relationships between economic prosperity and life expectancy.
- Addressed missing or zero GDP values to maintain data integrity.
- Life Expectancy and Mortality Metrics

_Explored how life expectancy relates to:_
- Adult mortality
- Infant deaths
- Under-five deaths
- Identified patterns such as high GDP correlating with high life expectancy and lower mortality rates.
- Classified countries into categories (e.g., "high" vs. "low" mortality rates) based on threshold-based criteria for adult, infant, and under-five mortality.

_Rolling Total of Adult Mortality_
- Computed cumulative adult mortality for the United States over time.
- Analyzed trends in cumulative mortality to identify periods of significant change or stabilization.

**Technologies Used**
- SQL: For querying and analyzing the dataset.
- Database Management: Leveraged SQL functions such as GROUP BY, HAVING, OVER, and CASE for advanced analytics.
- Data Cleaning: Applied filtering conditions to exclude invalid or missing values, ensuring accurate analysis.
