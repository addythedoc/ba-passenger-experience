**📌 Overview**

This project explores customer experience and service ratings for British Airways using public review datasets. After downloading the raw Excel/CSV files, I cleaned and prepared the data, joined multiple datasets, and built an interactive Tableau dashboard published on Tableau Public.
The dashboard allows users to explore customer satisfaction across continents, cabin classes, traveller types, aircraft models, and review timelines.
This project highlights skills in Tableau, Data Cleaning, Visualization, Insight Generation, and analytical storytelling.

**📂 Dataset**
Datasets Used:

ba_reviews.csv – Contains detailed review data, ratings, traveller type, seat type, route, aircraft, and recommendation status


Countries.csv – Country → Continent/Region mapping for geographic analysis


Rows: ~3,000
 Columns: Review details, aircraft type, route, traveller demographics, sub-ratings (seat comfort, food, entertainment, cabin staff), and overall score
Target Insights:
Customer satisfaction by geography


Service quality trends


Aircraft-wise and cabin-wise experience differences


Key areas where British Airways performs well or poorly



**🛠 Tools & Technologies**

Tableau Public – Dashboard creation & interactive visualization


Excel / CSV – Data cleaning and initial preprocessing


Tableau Desktop – Data joining, calculated fields, cleaning filters


GitHub – Project documentation & sharing


**📘 Project Steps**

1. Data Loading & Cleaning (Excel + Tableau)
Downloaded CSV datasets


Standardized column names


Removed invalid/placeholder values (-1 → NULL)


Created clean rating fields (Seat Comfort, Entertainment, Food, Value, etc.)


Joined country lookup table to add Continent & Region


Extracted Review Month & Year



2. Data Modeling in Tableau
Joined ba_reviews.csv with Countries.csv on reviewer location


Built calculated fields for:


Cleaned sub-ratings


Review month


Verified vs. non-verified reviews


Recommendation flag



3. Interactive Dashboard Development (Tableau Public)
The dashboard includes:
Global Map: Average customer rating by country


KPIs: Avg rating, seat comfort, entertainment, food, value for money, cabin staff service


Trend Chart: Rating over months (2017–2023)


Aircraft Analysis: Comparison of ratings and review counts across major aircraft types


Filters: Continent, cabin class, traveller type, aircraft type, service metric



4. Publishing & Sharing
Dashboard published on Tableau Public with filters, tooltips, and ratings ready for user exploration.

📊 **Results & Insights (Summary)**

Cabin Staff Service consistently receives the highest scores


Entertainment and Food & Beverages show the weakest performance across all cabin types


Wide-body aircraft like the Boeing 747-400 and Boeing 787 receive better experience ratings


Ratings vary significantly by continent; some regions report lower satisfaction overall


Economy passengers show large variability in ratings vs. Premium/Business Class



▶ **How to View This Project**

1. View Interactive Dashboard (Recommended)
👉 https://public.tableau.com/app/profile/aditya.kumar2854/viz/BritishAirwaysExperience_17617518713330/Dashboard1
2. Explore the Project Files (GitHub Repository)
/data → Raw datasets


/tableau → Tableau workbook (.twbx)


/screenshots → Static images of the dashboard


/Dashboard.pdf → Non-interactive PDF version


No installation required — everything is viewable directly.

📧 **Contact**

For questions, collaboration, or feedback:
 Aditya Kumar — Data Analyst | Epidemiology | Tableau | SQL | Python
 📩 Email: neplusultraa@gmail.com
 🔗 Tableau Public: https://public.tableau.com/app/profile/aditya.kumar2854

