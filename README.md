# Netflix-Dataset

📌 Objective

 - The objective of this project is to uncover key trends and improve data quality in the Netflix dataset by applying structured data cleaning, preparation, and analytical techniques.

📂 Data Collection

 - Dataset imported from Excel into Power Query for transformation and analysis.

🔎 Understanding the Data

 - During exploration, the following issues were identified:
 - Null values in the Age Certification column.
 - Null values in the IMDB Votes column.

🧹 Data Cleaning

Age Certification:
 - Missing values replaced with "Not Available" to ensure consistency.
   
IMDB Votes:
 - Missing values imputed with 1 since vote counts cannot be randomly assumed.

⚙️ Data Preparation

 - Feature Engineering: Created a new column Impact Score = IMDB Score × IMDB Votes to better capture content popularity and influence.

📊 Analysis

After data cleaning and preparation, the following analyses were conducted:

 - Most Rated Movies/Shows: Identified top-performing content based on IMDB votes and ratings.
 - Runtime Over Years: Analyzed how average runtime of content has changed across different years.
 - Number of Releases Over Years: Tracked Netflix content growth trends year by year.
 - Correlation Between IMDB Score & Rating: Explored the relationship between scores and audience ratings to assess content quality perception.

🚀 Tools & Technologies

 - Excel → Data Import & Initial Exploration
 - Power Query → Data Cleaning & Transformation
 - Power BI → Interactive Reports & Dashboards

✅ Key Outcomes

 - Improved dataset reliability with consistent and usable values.
 - Created a new metric (Impact Score) to highlight content popularity.

Generated insights on content trends, ratings, and Netflix growth over years.

Built an interactive Power BI dashboard to visualize findings effectively.
