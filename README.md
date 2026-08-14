# Netflix Analytics Tableau Dashboard

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Data Visualization](https://img.shields.io/badge/Data_Visualization-0078D4?style=for-the-badge)

An interactive Tableau dashboard designed to explore and analyze Netflix's global content catalog. This project provides visual insights into content distribution, age ratings, popular genres, content growth over time, and geographic production trends.
---

## 📸 Dashboard Overview
<img width="1920" height="1080" alt="Und" src="https://github.com/user-attachments/assets/d6ceab03-e90c-4ccd-95ac-62658b3be277" />


---

## 📸 Dashboard Overview

*(Tip: Replace `path/to/dashboard-image.jpg` with the relative path to your screenshot once uploaded to your repository)*

![Netflix Dashboard Screenshot](path/to/dashboard-image.jpg)

---

## 📊 Key Features & Visualizations

* **Selected Title Spotlight:** Displays specific metadata for highlighted titles including Title, Release Year, Added Date, Rating, Duration, Genre, and Description.
* **Distribution Breakdown:** Interactive pie chart showcasing the breakdown between **Movies (68.42%)** and **TV Shows (31.58%)**.
* **Content Ratings Analysis:** Bar chart visualizing maturity ratings across the library (led by `TV-MA`, `TV-14`, and `TV-PG`).
* **Top 10 Genres:** Highlights the most frequent genres on the platform, led by Documentaries and Stand-Up Comedy.
* **Growth Over Time:** Area chart tracking the exponential increase in content added to Netflix from 2008 through recent years (peaking around 2019).
* **Geographic Map:** Interactive world map mapping content volume by country of production (major hubs include the United States, India, UK, Canada, and Brazil).

---

## 🛠️ Tools & Technologies Used

* **Business Intelligence Tool:** [Tableau Desktop / Tableau Public](https://www.tableau.com/)
* **Data Source:** Netflix Movies and TV Shows Dataset (CSV)

---

## 🚀 How to View the Dashboard

1. **Tableau Public (Interactive Online):**
   * View the live interactive version on [Tableau Public](INSERT_YOUR_TABLEAU_PUBLIC_LINK_HERE).

2. **Tableau Desktop (Local):**
   * Clone this repository:
     ```bash
     git clone [https://github.com/YOUR-USERNAME/netflix-tableau-dashboard.git](https://github.com/YOUR-USERNAME/netflix-tableau-dashboard.git)
     ```
   * Open the `.twbx` file directly in **Tableau Desktop** or **Tableau Reader**.

---

## 📂 Repository Structure

```text
├── data/
│   └── netflix_titles.csv       # Source dataset
├── dashboard/
│   └── netflix_dashboard.twbx   # Tableau Packaged Workbook
├── assets/
│   └── dashboard_preview.jpg    # Screenshot for README
└── README.md                    # Project documentation
