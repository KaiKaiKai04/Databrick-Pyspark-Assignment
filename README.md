# Databrick-Pyspark-Assignment

### Assignment Summary – Big Data Modelling & Management (IT2312)

This project focuses on large-scale data ingestion, processing, and exploration using Databricks and PySpark to derive actionable business insights from a real-world movie ratings dataset. The objective was to analyse audience preferences and identify characteristics of both highly rated and poorly rated movies to support strategic decision-making in a film production context 


Using the MovieLens 25M dataset, which contains over 25 million ratings and 1 million tags, the project ingested and processed large datasets (movies.csv, ratings.csv, tags.csv) within a Databricks environment. All transformations and analyses were implemented strictly using PySpark and Pandas DataFrames, adhering to the constraint of no SQL usage.

### The analysis involved:

- Identifying frequently occurring niche and descriptive tags outside common genres

- Evaluating movies associated with negative tags (e.g. boring, overrated) and analysing their average ratings

- Analysing movies with positive tags (e.g. great acting, inspirational) to understand drivers of high audience satisfaction

- Segmenting ratings into defined rating ranges to examine tag distribution across different quality levels

- Filtering and aggregating tag occurrences to reveal meaningful patterns at scale

The project concludes with business-oriented insights that highlight how tag-based analysis can inform content strategy, recommendation systems, and marketing decisions, while demonstrating efficient big data processing techniques such as early aggregation and broadcast joins for scalable analytics.

### Technologies Used

- Databricks

- PySpark DataFrames

- Pandas

- MovieLens 25M Dataset

### Key Learning Outcomes

- Ingested and processed large-scale datasets in Databricks

- Applied PySpark DataFrame operations for big data exploration

- Performed tag-based sentiment and quality analysis at scale

- Derived business insights from structured and semi-structured data

- Demonstrated scalable and resource-efficient data processing techniques
