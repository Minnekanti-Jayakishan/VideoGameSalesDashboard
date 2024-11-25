# Video Game Sales Dashboard

## Overview

This project features an interactive Tableau dashboard that analyzes video game sales data across multiple dimensions, such as genre, platform, publisher, and sales trends over time. The dashboard provides insights into the most successful games, platforms, and genres, helping understand the video game industry's performance from 1980 to 2020.

[View the Interactive Dashboard on Tableau Public](https://public.tableau.com/views/gamesdashboard_Jayakishan/Games?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Key Features of the Dashboard
- **Total Sales by Genre**: A bar chart showcasing the total sales for each video game genre.
- **Sales by Years and Genre**: A stacked area chart depicting how game sales evolved over time for different genres.
- **Top 10 Platforms by Sales**: A bubble chart visualizing the top gaming platforms based on total sales.
- **Top 10 Games by Sales**: A horizontal bar chart listing the best-selling video games.
- **Top 10 Publishers by Sales**: A treemap highlighting the top publishers in terms of total sales.

## Insights Derived
- **Top Genre**: Action games dominate the market with the highest sales figures, followed by sports and shooter genres.
- **Platform Success**: The Nintendo Wii and Xbox 360 are among the most successful platforms by sales.
- **Best-Selling Game**: *Wii Sports* tops the list of best-selling games, followed by *Grand Theft Auto V*.
- **Sales Trends**: Video game sales peaked around 2008-2010, indicating a boom in the industry during that period.

## Dataset
The data used in this analysis includes:
- Sales data of video games across regions.
- Information about genres, platforms, publishers, and sales figures.

### Accessing the Dataset
The dataset used for this analysis is included in the `data/` folder as `vgsales.csv`.

## Folder Structure
TABLEAU-DASHBOARD-VIDEOGAMEANALYSIS/
│
├── index.html               # HTML file linking to Tableau dashboard
├── README.md                # Project overview and instructions
├── dashboard_screenshots/   # Folder for all screenshots
│   └── dashboard_preview.png   # Main screenshot of the dashboard
│
├── tableau_workbook/        # Folder for Tableau files
│   └── gamesdashboard.twbx     # Packaged Tableau workbook file
│
├── data/                    # Folder for raw or cleaned datasets
│   └── vgsales.csv.csv   # The dataset used in the analysis

## Instructions to View the Dashboard
### Option 1: Tableau Public
- Visit the interactive dashboard hosted on Tableau Public: [Open Dashboard](https://public.tableau.com/views/gamesdashboard_Jayakishan/Games?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

### Option 2: Open Locally Using the HTML File
- Open the `index.html` file in your browser to view the link to the Tableau dashboard.

### Option 3: Open the Tableau Workbook
1. Navigate to the `tableau_workbook/` folder.
2. Open the `gamesdashboard.twbx` file in Tableau Desktop.

## Tools Used
- **Tableau**: For data visualization and creating the interactive dashboard.
- **Dataset Preparation**: Data was preprocessed and cleaned before importing into Tableau.

## Future Enhancements
- Add region-specific insights to analyze sales by geography.
- Include detailed annotations for each visualization to explain key trends.
- Explore predictions of future sales using machine learning (future projects).

## License
This project is open-source and available under the [MIT License](LICENSE).