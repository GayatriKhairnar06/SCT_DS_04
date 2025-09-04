# 🚦 UK Road Accident Data Analysis
📌 Project Overview

This project analyzes the UK Road Accident dataset (2005–2015). The dataset is large (≈3.6 GB), so data type optimization and memory management techniques are applied before performing Data Cleaning & Exploratory Data Analysis (EDA).

The goal of this task is to:

Perform data cleaning (handling missing values, duplicates, and inconsistent types).

Optimize memory usage using data type conversion.

Conduct exploratory data analysis (EDA) to identify relationships between variables and highlight patterns & trends in road accidents.

📊 Dataset

Source: UK Department for Transport

Size: ~3.6 GB

Format: CSV

Description: Contains records of road accidents with details such as:

Date & Time of accident

Location (latitude, longitude, urban/rural)

Weather conditions

Road type & surface

Vehicle details

Casualties involved

⚙️ Steps Performed
1️⃣ Data Loading & Optimization

Used pandas with dtype conversion to minimize memory usage.

Converted object columns to category.

Converted integer & float columns to smaller precision (int8, int16, float32).

2️⃣ Data Cleaning

Handled missing values in weather, road surface, and location.

Removed duplicate accident records.

Standardized categorical values.

3️⃣ Exploratory Data Analysis (EDA)

Accident trends by year & month.

Time of day (peak accident hours).

Accidents by road type & weather conditions.

Severity analysis (fatal, serious, slight).

Geographical distribution of accidents.

4️⃣ Visualization

Line plots for accident trends.

Heatmaps for correlation between numerical variables.

Bar charts for categorical features (road type, weather, light conditions).

Pie charts for severity distribution.

📂 Project Structure
UK-Road-Accident-EDA/
│── data/                 # Dataset (not uploaded due to large size)
│── notebooks/            # Colab/Jupyter notebooks
│── scripts/              # Python scripts for data cleaning & EDA
│── outputs/              # Saved charts/plots
│── README.md             # Project documentation

🚀 How to Run

Clone the repository:

git clone https://github.com/yourusername/UK-Road-Accident-EDA.git
cd UK-Road-Accident-EDA


Install dependencies:

pip install -r requirements.txt


Run Jupyter Notebook / Colab for EDA:

jupyter notebook notebooks/EDA.ipynb

📈 Sample Insights (EDA)

✔ Most accidents occur during rush hours (8-9 AM & 5-7 PM).
✔ Urban areas report higher accident frequency but rural roads have higher severity.
✔ Poor weather conditions (rain, fog, snow) correlate with higher accident severity.
✔ Weekend accidents show a different distribution compared to weekdays.

🛠️ Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn)

Google Colab / Jupyter Notebook

GitHub for version control

📌 Future Work

Build predictive models (Logistic Regression, Random Forest) for accident severity.

Develop interactive dashboards (Plotly, Streamlit).

Perform geospatial analysis using Folium/Geopandas.

👩‍💻 Author

Gayatri Khairnar
📍 Data Science Enthusiast | Python | Machine Learning | Analytics
