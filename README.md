# 🎓 Baccalaureate Exam Results Dashboard

## Project Overview

This project presents an **interactive dashboard** designed to help public authorities explore exam results data and identify regions and educational tracks in France that may require targeted support. The dataset includes baccalaureate pass rates for the 2023 and 2024 exam sessions, broken down by department, education track and gender. The dashboard was developped using Power BI Desktop.

Explore the final written report online at the following link:
- https://mu-05.github.io/posts/2025-10-08-baccalaureate-success-rate/

## Dataset Source

The dataset used in this project was downloaded on **2025-09-22** from French Ministry of Education's open data portal, specifically the dataset titled [Réussite au baccalauréat par département](https://data.education.gouv.fr/explore/dataset/fr-en-baccalaureat-par-departement). 

Check out the **Informations** tab on the dataset page to view the full documentation.

## Objectives

- Develop a **user-friendly dashboard** to visualize the results from baccalaureate exam sessions
- Identify regions, departments and education tracks that require **targeted support**
- Provide data-driven **recommmendations** to help reduce disparities in baccalaureate pass rates

## Tools & Technologies

- Excel - for restructuring the source file
- Power Query - for data loading and transformation 
- Power BI - for building the interactive dashboard
- Quarto - for generating a clean, shareable HTML report

## Repository Structure

```plaintext
baccalaureate_success_rate/
│
├── dashboard/
│   └── baccalaureate_dashboard.pbix           # Power BI dashboard file
│
├── data/
│   └── source/
│       └── baccalaureate_source.csv           # Raw source data
│   └── transformed/
│       └── baccalaureate_transformed.xlsx     # Cleaned/prepared dataset
│       └── departments.csv                    # Geographical data
│       └── pass_rates.csv                     # Success rate data
│
├── report/
│   └── images/
│       └── dashboard_screenshot.png           # Screenshot of the dashboard
│       └── data_model.png                     # Diagram of the data model
│   └── videos/
│       └── dashboard_video.mp4                # Demonstration video
│   └── baccalaureate_report.qmd               # Quarto report file
│   └── baccalaureate_report.html              # Rendered HTML report
│   └── baccalaureate_report_files/            # Supporting files for report output
│
├── README.md                                  # Project overview
├── .gitignore                                 # Files to ignore in Git
└── baccalaureate_success_rate.Rproj           # RStudio project file
```

## How to use ?
If you’d like to explore the project in more detail or run it locally, follow these steps:
1. **Download the repository** <br>
   Click the green "**Code**" button at the top right of the repository and select "**Download ZIP**".
2. **Extract the ZIP file** <br>
   Unzip the downloaded file to a folder on your computer.
3. **Open the Power BI dashboard** <br>
   Launch `baccalaureate_dashboard.pbix` using Power BI Desktop (make sure it's installed).
4. **Interact with the dashboard** <br>
   Explore the data by clicking on the visual elements in the report.
5. **View the data transformation process** <br>
   Click "**Transform data**" under the **Home** tab in Power BI to open **Power Query** and review the data cleaning and preparation steps.
