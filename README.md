# Python Mini Project — Restaurant Data Analysis

**Author:** Divya Sharma  
**Date:** 19th September 2025  

---

## 📌 Project Overview
This mini project performs exploratory data analysis (EDA) on a food delivery dataset using Python (Jupyter Notebook).  
The goal is to analyze cost, ratings, and patterns in the dataset to answer specific questions.  

---

## 📖 Problem Statement
The tasks for this mini project are as follows:

1. Perform data exploration on the given restaurant dataset.  
2. Handle missing values and duplicates appropriately.  
3. Convert object-type columns into numeric where applicable.  
4. Create new derived columns (for example: region, cost categories).  
5. Analyze restaurant ratings, price range, and cuisine patterns.  
6. Draw correlation plots and other visualizations.  
7. Write insights and conclusions based on the findings.  

---

## 📂 Repository Structure
├── notebooks/
│ └── Python_mini_project_.ipynb # Jupyter notebook with full solution
├── data/
│ └── food_dely.csv.zip # Zipped full dataset
└── README.md # Documentation and problem statement


---

## 📊 Dataset
- The dataset (`food_dely.csv.zip`) contains restaurant information such as:  
  - City, country, latitude/longitude  
  - Average cost for two  
  - Price range  
  - Aggregate rating  
  - Votes and reviews  
  - Availability of delivery/takeaway options  

👉 Please unzip `food_dely.csv.zip` before running the notebook.  


import zipfile
with zipfile.ZipFile("data/food_dely.csv.zip", "r") as zip_ref:
    zip_ref.extractall("data/")
    
---

⚙️ How to Run

1. Clone this repository or download as ZIP:
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME

2. Install required libraries:
pip install -r requirements.txt

3. Launch Jupyter Notebook
4. Open notebooks/Python_mini_project_.ipynb and run cells step by step.

✅ Requirements

1. Python 3.x
2. Libraries:
   
      1.pandas
   
      2.numpy
   
      3.matplotlib
   
      4.seaborn
   
      5.scikit-learn
   
      6.jupyter
   

📈 Key Outcomes

1. Cleaned and preprocessed restaurant dataset.
2. Insights on restaurant ratings, costs, and regional distribution.
3. Correlation analysis and visualizations of key attributes.
4. Actionable conclusions from the EDA.

📝 License

This project is released under the MIT License.
You are free to use, modify, and distribute it with attribution.
