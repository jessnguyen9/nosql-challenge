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

Certain **local authorities** had a disproportionately high number of establishments with a hygiene score of 0, indicating serious food safety risks.

Aggregation techniques were used to rank these areas, highlighting where regulators should focus inspections and interventions.

2. **High-Rated Establishments & Customer Preferences**

Establishments in **major cities** (e.g., London) tend to have higher ratings, suggesting that urban businesses may face greater consumer scrutiny and competitive pressure to maintain high standards.

Filtering by location and rating thresholds helped identify **the top 5-star-rated food businesses** in key areas.

3. **Geographic & Business Type Trends**

**Cafés, takeaways, and mobile vendors** showed more hygiene issues compared to **hotels and restaurants**, likely due to differences in operational complexity and food handling practices.

Geospatial analysis revealed clusters of high-risk businesses, suggesting that certain neighborhoods may have systemic food safety challenges.

## How Was The Dataset Cleaned?
**Duplicate Entries:** Checked for and removed duplicate records to ensure data accuracy.

**Missing Values:** Certain establishments had pending ratings or missing hygiene scores, requiring careful handling to avoid bias.

**Inconsistent Formatting:** Some fields, like business types and addresses, contained inconsistent text values, which were standardized for analysis.

**Geolocation Errors:** Longitude and latitude fields were sometimes missing or incorrect, requiring cross-referencing with local authority data.

## Challenges
**Data granularity:** Some records lacked full details (e.g., hygiene scores not yet assigned). This made it difficult to analyze trends in certain local authorities.

**Nested Data Structures:** MongoDB’s NoSQL format required efficient querying and data extraction to work with embedded documents.

## Future Improvements
Integrate real-time updates for hygiene ratings.

Use visualization tools (Matplotlib, Seaborn) for better trend analysis.

Develop an API for querying establishments based on dynamic filters.

## Conclusion
This analysis leveraged MongoDB and PyMongo to explore food establishment ratings, add new businesses, and derive insights on hygiene trends. The findings can help regulators and businesses improve food safety and compliance.
