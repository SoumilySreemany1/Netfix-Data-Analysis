1. Project Title

Netflix Content Data Analysis Using Excel

2. Project Overview

This project presents a structured analysis of a Netflix-like content dataset, transforming raw data into meaningful insights through cleaning, pivot tables, and dashboard visualization.

The workflow follows a complete data analytics pipeline:

Raw dataset → Data cleaning → Pivot analysis → Dashboard creation

The final dashboard provides a compact and interactive view for understanding content trends and financial performance.

Key Objectives
Analyze distribution of content types (Movies, TV Series, etc.)
Compare production budget vs box office revenue
Evaluate average IMDb ratings and duration across content types
Identify country-wise contribution to content production and revenue
Create a dashboard for quick business insights and decision support
3. Project Structure
Folder	File	Description
Raw Dataset	Movies.csv	Original dataset containing raw content data
Clean Dataset	Netflix Movies Cleaned Dataset.xlsx	Cleaned and structured dataset used for analysis
Pivot Analysis	Pivot Tables.xlsx	Contains pivot tables and summarized insights
Dashboard	Dashboard.png	Final visual dashboard output
4. Data Dictionary
Column Name	Data Type	Description
movie_id	Text	Unique identifier for each record
content_type	Text	Type of content (Movie, TV Series, etc.)
genre_primary	Text	Main genre
genre_secondary	Text	Secondary genre
release_year	Integer	Year of release
duration_minutes	Integer	Runtime duration
rating	Text	Content certification
language	Text	Language of content
country_of_origin	Text	Production country
imdb_rating	Decimal	IMDb score (0–10)
production_budget	Decimal	Budget of production
box_office_revenue	Decimal	Revenue generated
number_of_seasons	Integer	Seasons (for series)
number_of_episodes	Integer	Episodes (for series)
is_netflix_original	Boolean	Indicates Netflix original content
added_to_platform	Date	Date added to platform
content_warning	Boolean	Content warning flag
5. Data Summary
Total Records: 1,040
Total Columns: 18
Missing Values: None
Release Year Range: 1953 – 2024
Average IMDb Rating: 6.27
Netflix Originals: ~30% of dataset
Content Warning Flagged: ~19%
Financial Overview
Total Production Budget: ~11.56 Billion
Total Box Office Revenue: ~67.19 Billion
Revenue-to-Budget Ratio: ~5.8x
6. Data Cleaning Notes
Split movie_id into structured components where required
Removed redundant or non-essential columns (like title in analysis sheet)
Standardized date formats for Excel compatibility
Verified zero missing values across all columns
Observations
Duplicate movie_id entries detected
Duplicate titles exist (expected for franchises or reused names)
Series-related fields are zero for non-series content
7. Analytics View
Pivot Table Analysis
By Content Type
Count of content
Average duration
Average IMDb rating
Total production budget
Total box office revenue
Total seasons and episodes
By Country
Content count
Total production investment
Total revenue generated
8. Dashboard Features

The dashboard includes:

Content distribution by type
Duration comparison across categories
Average IMDb rating insights
Investment vs revenue visualization
Country-wise financial comparison

These visuals provide a quick and effective way to interpret the dataset.

9. Tools Used
Microsoft Excel
Pivot Tables
Pivot Charts
Data Cleaning Techniques
Dashboard Design
10. Conclusion

This project demonstrates how raw entertainment data can be transformed into meaningful insights using Excel.

Key Insights
Movies dominate both in volume and revenue contribution
Overall revenue significantly exceeds production investment
USA leads in both production and earnings
Content type influences duration and ratings

The dashboard serves as a strong foundation for content strategy analysis and reporting.

11. Future Enhancements
Add time-based trend analysis (monthly/yearly)
Compare Netflix Originals vs Non-Originals
Build interactive slicers for dashboard filtering
Improve data validation for duplicate handling
Expand analysis using advanced tools (Power BI / Python)
