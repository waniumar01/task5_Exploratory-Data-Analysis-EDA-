# Task 5: Exploratory Data Analysis (EDA) – Titanic Dataset

## Objective
The objective of this task is to perform Exploratory Data Analysis (EDA) to extract meaningful insights using statistical and visual analysis techniques.

## Dataset
- **Titanic Dataset**
- Source: Kaggle  
  https://www.kaggle.com/c/titanic  
- File used: `train.csv`

## Tools Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Google Colab  

## Steps Performed
- Loaded and inspected the dataset using `.info()` and `.describe()`
- Checked for missing values and verified data types
- Performed univariate analysis using histograms and boxplots
- Conducted bivariate analysis using countplots and scatter plots
- Performed multivariate analysis using pairplots
- Analyzed feature correlations using a heatmap
- Documented observations for each visualization

## Key Insights
- Most passengers were between **15 and 40 years old**
- Fare distribution is **right-skewed** with several high-value outliers
- **Female passengers** had significantly higher survival rates than males
- Passengers who paid **higher fares** had better chances of survival
- Passenger class shows a **negative correlation** with survival
- Age has a **weak correlation** with survival

## Conclusion
The EDA revealed clear patterns influencing passenger survival, particularly gender, fare, and passenger class. These insights can be further leveraged for feature engineering and predictive modeling.

---
