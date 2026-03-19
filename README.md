# 🎲 Predicting Board Game Ratings Using Machine Learning

## 📌 Overview
This project focuses on analyzing and predicting board game ratings using machine learning techniques. The dataset is sourced from BoardGameGeek (via Kaggle) and includes various attributes such as game complexity, playtime, and player count.

The project follows a **data-centric pipeline**, moving from raw data preprocessing to exploratory data analysis (EDA), with the goal of understanding the factors that influence board game ratings.

---

## 🎯 Problem Statement
With thousands of board games available, it is difficult to determine which features contribute to higher user ratings. This project aims to analyze these features and build a foundation for predicting board game ratings based on their characteristics.

---

## 👥 Target Audience
- Board game designers  
- Game publishers  
- Data analysts  
- Recommendation system developers  

---

## 🤖 Why Machine Learning?
The relationship between board game attributes and ratings is complex and non-linear. Traditional rule-based approaches are insufficient, whereas machine learning models can uncover hidden patterns and provide more accurate predictions.

---

## 📊 Dataset
- Source: Kaggle (BoardGameGeek dataset)  
- Includes:
  - Game complexity (weight)
  - Playtime
  - Player count
  - User ratings  

---

## ⚙️ Project Workflow

```
Raw Data → Data Cleaning → Feature Engineering → EDA → Modeling (Future Work)
```

---

## 🧹 Data Preprocessing
- Handled missing values  
- Removed duplicate records  
- Managed outliers  
- Encoded categorical features  
- Normalized numerical variables  

---

## 📈 Exploratory Data Analysis (EDA)
Performed using `EDA.ipynb`:

### Key Analyses:
- Distribution plots (ratings, complexity, playtime)  
- Correlation heatmap  
- Feature impact analysis (complexity vs rating, playtime vs rating)  

### 🔍 Key Insights:
- Most board games have moderate to high ratings  
- Complexity (weight) shows a slight positive relationship with ratings  
- No single feature dominates — ratings depend on multiple interacting factors  

---

## 📂 Repository Contents

```
.
├── README.md
├── .gitignore
├── AI_Project.ipynb              # Data cleaning & preprocessing
├── EDA.ipynb                    # Exploratory Data Analysis
├── AI_Project_Report.pdf        # Final LaTeX report
```

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📄 Report
The project includes a detailed technical report (`AI_Project_Report.pdf`) covering:
- Problem Definition  
- Data Acquisition  
- Data Cleaning  
- Feature Engineering  
- Exploratory Data Analysis  

---

## 🔮 Future Work
- Train regression models to predict ratings  
- Compare different ML models (Linear Regression, Random Forest, etc.)  
- Build a recommendation system  
- Deploy as a web application  

---

## 👨‍💻 Contributors
- Fahad Aftab(23L-2609), Shaheer Ali(23L-2525), Farhan Rafiq(22L-7507)

---

## 📌 Note
Large datasets are not included in this repository as per project guidelines. All processing steps are documented in the provided notebooks.
