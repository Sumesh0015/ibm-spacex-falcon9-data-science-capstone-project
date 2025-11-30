# 🚀 SpaceX Falcon 9 – Data Science Capstone Project
IBM Data Science Professional Certificate
📌 Project Overview

This repository contains the complete end-to-end capstone project required for the IBM Data Science Certification.
The main objective is to predict whether the first stage of a SpaceX Falcon 9 rocket will successfully land, enabling accurate launch cost estimation for commercial clients.

The project includes API data collection, web scraping, data wrangling, EDA, machine learning, mapping with Folium, and a fully interactive Plotly Dash Dashboard.

📁 Repository Structure

Your current structure (as visible in the repo):

📦 ibm-spacex-falcon9-data-science-capstone-project
│
├── 1_spacex-data-collection.ipynb
├── 2_webscraping.ipynb
├── 3_spacex-Data wrangling.ipynb
├── 4_EDA-SQL.ipynb
├── 5_EDA-data-viz.ipynb
├── 6_launch_site_location.ipynb
├── 7_dash_app.py
├── 8_SpaceX_Machine Learning Prediction.ipynb
│
├── dataset.csv
│
├── Launch-site-proximity-on-map.png
├── Spacex-launch-record-dashboard.png
├── Spacex-launch-sites-on-map.png
├── Success-Failure-outcome-on-map.png
├── spacex-payload vs success.png
│
├── LICENSE
└── README.md

🧪 Project Workflow
1️⃣ Data Collection

Retrieved launch data using the SpaceX REST API

Converted JSON results into a clean dataframe

Exported as dataset.csv

2️⃣ Web Scraping

Scraped Falcon 9 launch tables from Wikipedia

Used BeautifulSoup for parsing

Cleaned and merged with API data

3️⃣ Data Wrangling

Removed irrelevant columns

Handled missing values

Created landing outcome labels

Feature engineering for ML

4️⃣ SQL-Based EDA

Analyzed success rate per launch site

Query-based filtering of payload range

Most frequent orbits and boosters

5️⃣ Python EDA & Visualizations

Scatter plots, bar charts, heatmaps

Folium maps for:

Launch site locations

Success/failure outcomes

Launch site proximity to highways, coastlines, and railroads

6️⃣ Machine Learning

Models tested:

Logistic Regression

Decision Tree

Support Vector Machine

K-Nearest Neighbors

Best performing model: Decision Tree Classifier (tuned)

7️⃣ Interactive Plotly Dash App

Your dashboard (7_dash_app.py) includes:

Launch site dropdown

Payload mass range slider

Interactive pie chart

Interactive scatter plot

🗂 Dataset

The dataset used for prediction:

📄 dataset.csv

Contains:

Flight Number

Launch Site

Booster Version

Orbit

Payload Mass

Landing Outcome (Class Label)

Launch Success

📊 Included Visual Outputs

These images are included in your repo and automatically displayed below:

🔹 Launch Sites on Map

🔹 Launch Success/Failure Map

🔹 Launch Site Proximity Analysis

🔹 Payload vs Success Plot

🔹 Final Dashboard

▶️ Running the Project
Run Jupyter Notebooks
jupyter notebook

Run the Dash App
python 7_dash_app.py


Open the local URL shown in your console.

📜 License

This project is released under the MIT License.
See the LICENSE file for details.

👤 Author

Sumesh
GitHub: https://github.com/Sumesh0015
