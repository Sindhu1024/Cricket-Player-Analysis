**Power BI Cricket Strike Rate Analysis Report**

This repository contains an end-to-end Power BI project analyzing strike rates from ODI matches played between India and South Africa.
The dataset was scraped directly from ESPN Cricinfo using Power BI’s built-in Web Connector, cleaned in Power Query, and modeled to create an interactive analytical dashboard.

📌 **Project Overview**

This project demonstrates:

Web scraping cricket statistics using Power BI

Cleaning & transforming scraped HTML tables in Power Query

Classifying strike rates into performance categories

Building dynamic visualizations in Power BI

Creating a structured .pbix report suitable for analysis and presentation

The main report file is included:

ESPN.pbix

📑 **Data Description**

Source: ESPN Cricinfo StatsGuru
https://stats.espncricinfo.com/ci/engine/stats/index.html

-Match Type: ODIs (One Day Internationals)

-Teams: India vs. South Africa

-Collection Method: Power BI Web Connector (HTML table scraping)

-Additional batting,bpwling and fielding metrics from ESPN statistics pages

-Cleaning: Performed fully in Power Query before loading into the model

📊 **Strike Rate Categories**

Strike rate values (0–200) were grouped into:

Category	Range
Very Low	0–50
Low	51–80
Moderate	81–120
High	121–150
Very High	151–200

These were used throughout the dashboard to segment and analyze player performance.

🖥 **Report Features**

-Strike-rate distribution visualizations

-Category-wise performance segmentation

-Player comparison charts

-Slicers for team/match filtering

-Clean and interactive dashboard design

🛠 **Technologies Used**

-Power BI Desktop

-Power Query (M Language)

-DAX

-Power BI Web Connector (for scraping)

No Python or external code was used.

📥 **How to Use**

Download the file:

ESPN.pbix


Open it in Power BI Desktop.

Interact with visuals, slicers, and filters.

Refresh data if needed (note: website structure may change).

📂 **Repository Structure**
📁 repository-root
│── README.md
│── ESPN.pbix        # Main dashboard file

📧 Contact

If you have suggestions, improvements, or questions, feel free to open an issue or reach out.
