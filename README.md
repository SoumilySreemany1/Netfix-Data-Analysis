# Netflix Movie Data Analysis Dashboard
Interactive Netflix-style content analysis dashboard using **Google Sheets** with pivot insights and investment vs return views.

---

## 1. Project Title
**Netflix Movie Data Analysis Using Google Sheets**

---

## 2. Project Overview

This project analyzes a Netflix-style content catalog to uncover insights on content distribution, financial performance, and audience-related indicators.

The workflow starts from raw data and proceeds through cleaning, pivot-table analysis, and dashboard visualization. The final output provides a compact analytical view that can support exploratory reporting and business-oriented content decisions.

### Key Objectives

- Analyze content mix across Movies, TV Series, Documentaries, and related formats
- Compare production investment against box office returns
- Evaluate average duration and IMDb rating by content type
- Assess country-level contribution to investment and returns
- Build a dashboard-ready Excel analysis layer from the raw dataset

---

## 3. Project Structure

| Folder | File | Description |
|---|---|---|
| Raw Dataset | `Raw Dataset/Movies.csv` | Original source dataset |
| Clean Dataset | `Clean Dataset/Clean movies.xlsx` | Cleaned workbook |
| Clean Dataset | `Clean Dataset/Clean movies - movies.pdf` | PDF export |
| Pivot Tables | `Pivot Tables and Calculations/Movies Pivot Data Analysis1.xlsx` | Pivot v1 |
| Pivot Tables | `Pivot Tables and Calculations/Movies Pivot Data Analysis2.xlsx` | Pivot v2 |
| Dashboard | `Dashboard/NetflixDashboardUsingLookerStudio.png` | Looker dashboard |
| Dashboard | `Dashboard/NetflixUserAnalysisDashboard.png` | User dashboard |

---

## 4. Data Dictionary

| Column Name | Data Type | Description |
|---|---|---|
| `movie_id` | Text | Unique identifier |
| `title` | Text | Movie title |
| `content_type` | Text | Movie/Series/Doc |
| `genre_primary` | Text | Primary genre |
| `genre_secondary` | Text | Secondary genre |
| `release_year` | Integer | Year |
| `duration_minutes` | Integer | Runtime |
| `rating` | Text | Certification |
| `language` | Text | Language |
| `country_of_origin` | Text | Country |
| `imdb_rating` | Decimal | IMDb score |
| `production_budget` | Decimal | Budget |
| `box_office_revenue` | Decimal | Revenue |
| `number_of_seasons` | Integer | Seasons |
| `number_of_episodes` | Integer | Episodes |
| `is_netflix_original` | Boolean | TRUE/FALSE |
| `added_to_platform` | Date | Added date |
| `content_warning` | Boolean | TRUE/FALSE |

---

## 5. Data Summary

- Total records: **1,040**
- Total columns: **18**
- Missing values: **0**
- IMDb average: **6.273**
- Revenue-to-budget ratio: **5.813x**

---

## 6. Analytics View

Includes pivot tables and dashboards showing:

- Content distribution  
- IMDb ratings comparison  
- Investment vs returns  
- Country-wise analysis  

---

## 7. Tools Used

- Microsoft Excel  
- Pivot Tables  
- Dashboard Design  

---

## 8. Dashboard Images

Below is the dashboard created for visual analysis:

<p align="center">
  <img src="Dashboard /Dashboard1.png" width="900">
</p>

---

Below is the dashboard created for user analysis:

<p align="center">
  <img src="Dashboard /Dashboard2.png" width="900">
</p>

## 9. Conclusion

- Movies dominate content and revenue  
- Strong ROI across dataset  
- USA leads in production and returns  

---

## 10. Future Enhancements

1. Add time-based trends  
2. Originals vs Non-originals analysis  
3. Data validation rules  
