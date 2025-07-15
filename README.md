# Task_04_Descriptive_Stats

## 📌 Overview

This project performs descriptive statistical analysis on 3 different datasets such as political ad data, facebook posts data and twitter data from the **2024 U.S. Presidential Election**,  using ** Pure Python's standard library** (no external dependencies), **Pandas** and **Polars**. The analysis includes the descriptive statistics of all three dataset's numerical and categorical columns.

## 🚀 How to Run the Code

1. **Make sure you have Python 3.x installed**.

2. **Place the dataset** in a known directory (e.g., `Downloads/period_03/`).

3. **Update the file path** in the script if needed:

   For example: ```python 
   filepath = 'C://Users//your_name//Downloads//period_03//2024_fb_ads_president_scored_anon.csv'


## Summary of findings or interesting insights

1.	Facebook ads dataset results
The script computes:
•	Overall descriptive stats for the column estimated_spend
o	Count, Mean, Min, Max, Standard Deviation
•	Top 10 most frequent entries in the bylines (campaign source) column
•	Grouped statistics by page_id (aggregating spend data per page)
Interesting Insights
•	The dataset contains 246,745 valid ad spend records.
•	The average ad spend per entry was around $1,061, but varied widely (up to $474,999).
•	Top campaign sources by ad count include:
o	HARRIS FOR PRESIDENT – 49,788 entries
o	HARRIS VICTORY FUND – 32,612 entries
o	DONALD J. TRUMP FOR PRESIDENT 2024, INC. – 15,112 entries
•	Some page_id groups had very consistent spend patterns, including pages with standard $49 spends and zero standard deviation.
Performance
Runtime for full analysis: ~11.26 seconds
Environment: Pure Python with no optimization or multithreading

2.	Facebook ads results
Total records analyzed: 14,398
Mean interactions: ~2,210 per post/page
Max interactions: 470,087 – showing highly viral posts
Standard deviation: ~13,066 – wide distribution and variance
Quartiles:
25%: 47 interactions
50% (median): 133 interactions
75%: 452 interactions
Top Page Category values:
PERSON: 9,453 entries
ACTOR: 3,304 entries
POLITICIAN: 2,595 entries
POLITICAL_CANDIDATE: 1,161 entries
Less common: ENTREPRENEUR, YOUTH_ORGANIZATION
Grouped by Facebook_Id, key insights:
Certain pages like a3fa0d15dd83... received up to 196,265 total interactions.
Some users/pages have extremely high engagement across many posts.



