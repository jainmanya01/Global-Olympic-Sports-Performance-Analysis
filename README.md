# Global Olympic Sports Performance Analysis

An end-to-end data analytics and web integration project analyzing historical Olympic data, athlete metrics, and regional performance trends, built with Python, Tableau, and Flask.

## Project Overview
This project explores global Olympic sports performance through interactive visualizations and a custom web user interface. It investigates medal distributions across countries, regional efficiencies, top-performing sports, and athlete statistics.

## Datasets Used
- `medal_results.csv`: Country-wise medal counts (Gold, Silver, Bronze, Total).
- `athletes.csv`: Individual athlete participation and biographical data.
- `games_summary.csv`: Historical Olympic games information and metadata.
- `alltime_country_rankings.csv`: Aggregated all-time standings for participating nations.

## Key Features & Visualizations
1. **Medals Per Country**: Comparative bar charts of total medals won by each nation.
2. **Top Sports**: Analysis of highest-yielding Olympic sports and disciplines.
3. **Athlete vs. Medals Scatter Plot**: Correlation analysis between athlete counts and medal success.
4. **Regional Efficiency**: Evaluation of medal conversion rates across different global regions.
5. **Interactive Storyboard**: A guided Tableau story navigating through global Olympic trends.

## Tech Stack
- **Data Analysis & Modeling**: Tableau Public, Python (Pandas)
- **Web Backend**: Flask (Python)
- **Frontend & UI**: HTML5, CSS3, Tableau Embedding API v3
- **Version Control**: Git & GitHub

## Step-by-Step Project Development Procedure
1. **Data Collection & Preparation**: Imported raw Olympic CSV files, cleaned missing fields, and structured data relationships.
2. **Feature Engineering**: Created custom calculated fields (such as `Gold Medal Ratio`) inside Tableau to evaluate performance quality.
3. **Visualization & Dashboarding**: Designed individual worksheets and assembled them into an interactive Storyboard (`Story1`).
4. **Publishing**: Published the complete workbook to Tableau Public.
5. **Flask Web Integration**: Embedded the live Tableau dashboard into a lightweight Python Flask web application using Tableau Embedding API v3 to bypass frame restrictions.

## How to Run Locally
1. Clone the repository and navigate to the project directory.
2. Install Flask:
   ```bash
 pip install flask
 python app.py
Open your browser and navigate to 
http://127.0.0.1:5000/
