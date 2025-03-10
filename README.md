# Establishment Ratings Analysis – Insights & Recommendations

## Overview
This project explores food establishment ratings in the UK using MongoDB and Python. The goal was to analyze hygiene scores, identify trends in food safety, and uncover geographic patterns in ratings. Through structured querying and analysis, key insights were derived to inform public health authorities, business owners, and consumers.

## Tools & Technologies Used
**MongoDB:** NoSQL database for storing and querying unstructured data.

**PyMongo:** Python library for interacting with MongoDB.

**Pandas:** Data analysis and transformation.

**Jupyter Notebook:** Interactive computing environment for data exploration.

**Python:** Primary language for data processing and querying.

## Key Insights & Findings
1. **Hygiene Risk Hotspots**

Certain local authorities had a disproportionately high number of establishments with a hygiene score of 0, indicating serious food safety risks.

Aggregation techniques were used to rank these areas, highlighting where regulators should focus inspections and interventions.

2. **High-Rated Establishments & Customer Preferences**

Establishments in major cities (e.g., London) tend to have higher ratings, suggesting that urban businesses may face greater consumer scrutiny and competitive pressure to maintain high standards.

Filtering by location and rating thresholds helped identify the top 5-star-rated food businesses in key areas.

3. **Geographic & Business Type Trends**

Cafés, takeaways, and mobile vendors showed more hygiene issues compared to hotels and restaurants, likely due to differences in operational complexity and food handling practices.

Geospatial analysis revealed clusters of high-risk businesses, suggesting that certain neighborhoods may have systemic food safety challenges.

**PART 2: UPDATE THE DATABASE**

1. Added New Restaurant

2. Removing Establishments in Dover

3. Data Type Conversions

**PART 3: EXPLORATORY ANALYSIS**

**Question 1**: Establishments with Hygiene Score Equal to 20

Displayed the establishments with a hygiene score equal to 20.

Converted the result to a Pandas DataFrame and displayed the first 10 rows.

**Question 2**: Establishments in London with RatingValue >= 4

Displayed the establishments in London with a RatingValue greater than or equal to 4.

Converted the result to a Pandas DataFrame and displayed the first 10 rows.

**Question 3**: Top 5 Establishments with RatingValue of 5, Sorted by Lowest Hygiene Score

Found the top 5 establishments with a RatingValue of 5.

Sorted the results by the lowest hygiene score, nearest to "Penang Flavours" restaurant.

Compared the geocode to find the nearest locations.

**Question 4**: Number of Establishments with Hygiene Score of 0 in Each Local Authority Area

Displayed the number of establishments in each Local Authority area with a hygiene score of 0.

Sorted the results from highest to lowest and displayed the top ten Local Authority areas.
