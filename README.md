# Analyzing 20 Years of Real Estate Sales Data (2001–2021)
## Tools: Python (Pandas, Matplotlib), Data Cleaning, Exploratory Data Analysis

In this project, I analyzed a large dataset of real estate sales across multiple towns from 2001 to 2021, focusing on sales trends, valuation, and pricing patterns. The dataset contained over 620,000 property sales records, including assessed values, sale amounts, property types, and addresses.

### Key Steps:
Data Cleaning:

Loaded raw CSV data (~620k rows, 13 columns), handled mixed data types, and removed irrelevant or NaN-heavy columns.

Dropped rows with missing values and made sure that no duplicate records remained.

Reindexed the dataset using unique serial numbers.

### Exploratory Data Analysis (EDA):

Identified properties sold for more than twice their assessed value (sales ratio < 0.5).

Extracted the top 10 single-family properties by highest assessed value and actual sale value.

Calculated sale-assessment differences to find:

Top 10 addresses with the largest positive gaps (under-assessed, high sale prices).

Top 10 addresses with the smallest gaps (high assessment accuracy).

Aggregated the number of properties listed per year, highlighting active vs. inactive sales periods.

### Key Takeaways:
Valuation insights matter: Many high-value transactions showed large discrepancies between assessed and sale values, indicating underestimation or market surges.

Single-family homes consistently ranked highest in both assessment and sales, underscoring their market strength.

Peaks in listings during 2020–2021 revealed shifts which could possibly be tied to external events (like pandemic-driven moves).

Technical growth: Strengthened skills in Python for data cleaning, exploratory queries, sorting, aggregation, and custom plotting using large, real-world datasets.
