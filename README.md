# Lab2_Control_Statements-EDA
This lab focuses on analyzing real-world Facebook dataset using Python. It covers data loading from CSV and Excel, examining structure, handling data quality, and computing descriptive statistics. Visualizations are used to interpret patterns, strengthening data analysis skills and practical understanding.


Overview:
This lab explores Facebook dataset files in both CSV and Excel formats to analyze user attributes and activity.
The project demonstrates:

Data Access – Comparing CSV vs. Excel formats.

Data Examination – Inspecting structure, types, and missing values.

Descriptive Statistics – Summarizing central tendency and dispersion.

Data Visualization – Lightweight plots for numeric features.

The goal is to understand how different file formats affect analysis, and to extract meaningful insights from user data.

Step 1: Data Access:
Uploaded both CSV and Excel files.

Compared shapes and column headers:

CSV: (715, 3) with limited columns.

Excel: (715, 18) with full structured attributes.

Conclusion: Excel preserved formatting and metadata more reliably, but both contained consistent content once interpreted.

Step 2: Data Examination::
Inspected column names, top and bottom rows, and data types.

Checked for missing values: None detected.

Dataset includes attributes such as:

Age, Photos, Tags, Albums, Gender, Employment, Profile, Cover, Orientation, Relationship, Posts, Replies, Children, Likes, Education, Events, Friends.

Step 3: Descriptive Statistics:
Generated summary statistics (df.describe()):

Count: 715 entries across all columns.

Mean Age: ~24.4 years.

Photos: Average ~724, with wide variation (std ~1265).

Tags: Average ~458, max >10,000.

Albums: Average ~19, max 172.

Likes: Average ~187, max 11995.

Key measures: count, mean, std, min, quartiles (25%, 50%, 75%), max.

Insights:

High dispersion in photo uploads and likes.

Age distribution skewed toward younger users.

Outliers present in tags and likes.

Conclusion::
CSV vs Excel: Both formats contained the same data, but Excel offered richer structure and metadata.

Data Examination: Dataset was complete, with no missing values.

Descriptive Statistics: Revealed central tendencies and wide dispersion in user activity metrics.

Visualization: Provided lightweight, interpretable plots for numeric features.

Overall, this lab demonstrated the importance of file format, descriptive statistics, and visualization in understanding social media datasets.
