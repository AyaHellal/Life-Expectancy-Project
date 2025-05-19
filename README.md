# Life-Expectancy-Project
🌍 WHO Life Expectancy Data Analysis Project
This data analysis project explores the WHO Life Expectancy Dataset, which includes a wide range of health and socio-economic indicators across different countries. The goal is to examine factors influencing life expectancy and build regression models to predict it based on key variables.

📌 Project Overview
This project demonstrates a complete data analysis pipeline, including:

Handling missing data and outliers

Exploratory Data Analysis (EDA)

Creating a Choropleth map to visualize global life expectancy trends

Performing Multiple Linear Regression and Polynomial Regression

Model refinement using Grid Search

Visual evaluation of regression results

📁 Dataset Information
Source: World Health Organization (WHO)

Access Link: Kaggle Dataset

Original File Name: Life Expectancy Data.csv

Cleaned File Name: Clean Life Expectancy Data.csv (used for regression modeling)

📊 Column Descriptions (Sample)
Column Name	Description
Country	Name of the country
Year	Year of record
Status	Economic classification: Developed or Developing
Life expectancy	Average number of years a person is expected to live at birth (Target)
Adult Mortality	Probability of dying between 15 and 60 years per 1,000 adults
Alcohol, BMI, GDP, Schooling	Lifestyle and socio-economic indicators
Immunization columns (Polio, Diphtheria, etc.)	Coverage rates for various vaccines

See the full dataset for all column descriptions.

🎯 Key Research Questions
📈 What factors truly influence life expectancy?

💰 Should countries with low life expectancy (<65) increase health expenditure?

👶 How do infant and adult mortality rates impact life expectancy?

🧬 What is the relationship between alcohol, nutrition, BMI, and life expectancy?

🏫 How does education (schooling) impact lifespan?

🌍 Do densely populated countries tend to have lower life expectancy?

🧪 What is the role of immunization in improving life expectancy?

🛠 Skills and Tools Used
Python Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, plotly

Data wrangling and missing value handling

Regression modeling (linear and polynomial)

GridSearchCV for hyperparameter tuning

Choropleth map creation with plotly and geojson

📂 Project Structure
🔍 Notebook 1: Life Expectancy Project.ipynb
Purpose:

Handle missing data and outliers

Perform Exploratory Data Analysis (EDA)

Create a Choropleth Map using countries.geo.json to visualize life expectancy trends by country

Files Used:

Life Expectancy Data.csv

countries.geo.json

📊 Notebook 2: Regression Project.ipynb
Purpose:

Build and evaluate regression models:

Multiple Linear Regression

Polynomial Regression

Grid Search for model tuning

Visualize prediction performance and compare results

Files Used:

Life Expectancy Data.csv

▶️ How to Run the Code
📁 Required Files
Ensure the following files are present in your working directory:

Life Expectancy Data.csv

Regression Project.ipynb

🔧 Installation
You can install the required Python libraries using:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn plotly
(Optional) Create and activate a virtual environment for project isolation:

bash
Copy
Edit
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

🚀 Running the Analysis
 Life Expectancy Projec.ipynb to explore and clean the dataset, and visualize global trends.

Open Regression Project.ipynb to run predictive modeling and evaluate regression performance.

📈 Sample Outputs
Choropleth map of life expectancy across countries

Correlation heatmaps and scatter plots

Regression evaluation metrics (R² score, MAE, RMSE)

Visual comparison of predicted vs. actual values

📬 Feedback
Have suggestions or ideas? Feel free to open an issue or contribute via pull request!



