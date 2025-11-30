🚀 SpaceX Falcon 9 Data Science Capstone Project

This project is part of the IBM Data Science Professional Certificate.
The goal is to predict whether the SpaceX Falcon 9 first stage will land successfully using data science techniques.

📘 Project Contents

This repository contains:

Dataset (SpaceX_Falcon9.csv)

Jupyter Notebook (full analysis + ML model)

Images (map & dashboard)

Machine Learning results

Final insights

🖼️ Project Images
🌍 Launch Site Map

images/map.png

📊 Final Dashboard

images/dashboard.png

📂 Dataset (Included in This Repository)

File: SpaceX_Falcon9.csv

This dataset includes:

Flight number

Launch site

Booster version

Payload mass

Orbit

Landing outcome (success/failure)

Booster reuse information

Latitude & longitude

👉 No external download needed — dataset is already included.

🤖 Machine Learning Results

Four models were tested to predict landing success:

Model	Accuracy
Logistic Regression	≈ 83% (Best)
Decision Tree	~78%
SVM	~80%
KNN	~75%

➡ Logistic Regression performed the best with the highest accuracy.

🧠 Final Insights

SpaceX’s landing success rate has improved over the years.

Payload mass and booster version strongly impact the probability of landing.

Cape Canaveral sites have higher landing success rates.

The ML model can predict whether the booster will land based on mission features.

▶️ How to Run

Install required libraries (Pandas, NumPy, Scikit-Learn, Plotly, Folium).

Open the notebook:

jupyter notebook notebooks/spacex_falcon9_project.ipynb

🙌 Acknowledgements

IBM Data Science Professional Certificate

SpaceX public data

Wikipedia API