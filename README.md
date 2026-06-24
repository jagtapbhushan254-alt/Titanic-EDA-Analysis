# Titanic EDA Analysis

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to identify factors influencing passenger survival.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Key Insights
- Female passengers had significantly higher survival rates.
- First-class passengers survived more often.
- Family size influenced survival probability.

## Key Findings

1. **Overall Survival Rate**
   - Approximately **38%** of the 891 passengers survived.

2. **Sex Was the Strongest Predictor**
   - Female survival rate: **~74%**
   - Male survival rate: **~19%**

3. **Passenger Class Had a Major Impact**
   - 1st Class: **~63%** survived
   - 2nd Class: **~47%** survived
   - 3rd Class: **~24%** survived

4. **Children Had Higher Survival Rates**
   - Passengers under 10 years old showed notably higher survival rates.

5. **Class and Sex Interaction**
   - 1st Class Females: **~97%** survival rate
   - 3rd Class Males: **~15%** survival rate

6. **Family Size Influenced Survival**
   - Passengers traveling alone had lower survival odds compared to those traveling with family members.

7. **Data Quality and Cleaning**
   - Age had approximately **20% missing values** and was imputed using the median.
   - Cabin had approximately **77% missing values** and was removed from the analysis.

## Visualizations

### Survival by Gender

![Survival by Gender](images/survival_by_gender.png)

### Survival by Passenger Class

![Survival by Class](images/survival_by_class.png)

### Correlation Heatmap

![Correlation Heatmap](images/correlation_heatmap.png)
  
## Files
- titanic_eda_guide1.ipynb : Complete EDA notebook
- requirements.txt : Required Python libraries

## Future Improvements

- Build a Titanic Survival Prediction model using Machine Learning.
- Compare Logistic Regression and Random Forest performance.
