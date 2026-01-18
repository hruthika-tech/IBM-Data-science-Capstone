
# SpaceX Falcon 9 Launch Analysis 🚀

## IBM Data Science Capstone Project

This project analyzes **SpaceX Falcon 9 launch data** to study **first-stage landing success** and build **predictive machine learning models**.  
It demonstrates an **end-to-end data science workflow**, from data collection to model evaluation.

---

## 📌 Project Overview

SpaceX’s Falcon 9 rocket is designed for reusability, significantly reducing launch costs.  
Predicting whether the first stage will successfully land is crucial for cost estimation and mission planning.

**Objective:**
- Analyze historical Falcon 9 launch data
- Identify factors affecting landing success
- Build machine learning models to predict landing outcomes

---

## 🛠️ Tools & Technologies Used

- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **SQL (SQLite)**
- **Folium (Maps)**
- **Dash (Interactive Dashboard)**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 📂 Project Structure
spaceX-Falcon-9-Launch-Analysis/
│
├── notebooks/
│ ├── spacex-data-collection.ipynb
│ ├── spacex-data-collection-api.ipynb
│ ├── spacex-data-wrangling.ipynb
│ ├── eda-sql-coursera_sqllite.ipynb
│ ├── SpaceX_Machine Learning Prediction.ipynb
│
├── presentation/
│ └── Spacex Falcon 9 launch analysis.pdf
│
└── README.md

---

## 🔍 Project Workflow

### 1️⃣ Data Collection
- Collected launch data using the **SpaceX REST API**
- Scraped additional information from **Wikipedia**
- Extracted launch site, payload, orbit, and landing outcomes

### 2️⃣ Data Wrangling
- Handled missing and inconsistent values
- Selected relevant features
- Created a binary target variable for landing success

### 3️⃣ Exploratory Data Analysis (EDA)
- SQL queries to analyze launch sites and mission outcomes
- Visual analysis using scatter plots, bar charts, and trend analysis

### 4️⃣ Interactive Visual Analytics
- **Folium maps** to visualize launch locations
- **Dash dashboard** for interactive exploration of payload vs success

### 5️⃣ Predictive Modeling
- Models used:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Decision Tree
- Hyperparameter tuning using **GridSearchCV**
- Best model achieved **~83% accuracy**

---

## 📊 Results & Insights

- Payload mass and orbit significantly affect landing success
- Certain launch sites show higher success rates
- Booster reusability improves with experience over time

---

## 📝 Note on Empty Cells

Some notebooks contain **empty cells**.  
These cells were **intentionally left blank** as part of the original **IBM Data Science Capstone lab structure** for optional practice and exploration.

✔️ All **required tasks**, **analyses**, **visualizations**, and **models** have been fully completed.  
✔️ No mandatory content is missing.

---

## 📈 Future Work

- Use larger and more recent datasets
- Apply advanced machine learning models
- Deploy the trained model as a web application

---

## 👤 Author

**Hruthikamamidala**  
IBM Data Science Capstone Project

---

⭐ *If you found this project useful, feel free to star the repository!*
