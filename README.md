# data-analyst-ravneet
# *Surviving the Titanic: Exploratory Data Analysis*  

## *📌 Project Overview*  
This project performs an *Exploratory Data Analysis (EDA)* on the *Titanic dataset* to uncover factors influencing passenger survival. Using Python (Pandas, Matplotlib, Seaborn), we analyze key features like *age, gender, class, and fare* to identify survival trends.  

---

## *🔍 Methodology*  

### *1. Data Collection & Preparation*  
- Loaded and cleaned the dataset (handled missing values, dropped irrelevant columns).  
- Converted data types for better analysis like, categorical encoding.  

### *2. Descriptive Statistics*  
- Analyzed numerical features (Age, Fare) and categorical distributions (Pclass, Sex).  
- Calculated survival rates across different groups.  

### *3. Data Visualization*  
- *Histograms & Boxplots*: Examined distributions of Age and Fare.  
- *Bar Charts*: Compared survival rates by gender, class, and age groups.  
- *Heatmaps*: Visualized correlations between numerical variables.  

### *4. Survival Analysis*  
- Gender: Women had a *74% survival rate* vs. *19% for men* (p < 0.0001).  
- Class: *1st-class passengers* had the highest survival rate (~63%).  
- Age: *Children (<12)* had better survival chances, especially in higher classes.  

---

## *💡 Key Insights & Findings*  
✔ *"Women and children first" policy was evident* – females and young passengers had significantly higher survival rates.  
✔ *Class disparity* – 1st-class passengers had *3x higher survival* than 3rd-class.  
✔ *Age mattered* – Children in 1st/2nd class were prioritized, while elderly passengers struggled.  

---

## *🎯 Conclusion & Next Steps*  
The analysis confirms *socioeconomic and demographic biases* in Titanic survival. Further steps could include:  
- *Predictive modeling* (Logistic Regression, Random Forest) to classify survival.  
- *Feature engineering* (family size = SibSp + Parch) for deeper insights.  
- *Hypothesis testing* to validate observed trends statistically.  

---

## *🛠 Technologies Used*  
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Google Colab
