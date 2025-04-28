# Titanic Data Analysis Project

## Objective
The objective of this project is to explore and extract insights from the Titanic dataset using basic statistical methods and visual exploration techniques. The focus is on identifying patterns, relationships, and key factors that influenced survival.

## Tools and Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The project uses three CSV files:
- `train.csv` — training dataset with features and survival labels.
- `test.csv` — testing dataset (without survival labels).
- `gender_submission.csv` — sample submission file for reference.

## Steps Followed

1. **Data Exploration**
   - Used `.info()`, `.describe()`, `.value_counts()` to understand basic structure and summary statistics.
   - Checked for missing values and data types.

2. **Visualization**
   - Plotted histograms to analyze the distribution of Age and Fare.
   - Created boxplots to observe outliers in Fare.
   - Used countplots to study survival distribution by Sex and Passenger Class.
   - Built a pairplot to identify trends between Fare, Age, Pclass, and Survival.
   - Plotted a heatmap to observe correlations between numerical features.

3. **Observations**
   - Gender (female), Passenger Class (first class), and Fare amount had strong relationships with survival.
   - Most passengers were young adults aged 20–40.
   - Majority of passengers boarded from Southampton.
   - Fare showed presence of outliers.
   - Age, Cabin, and Embarked columns contained missing data.

4. **Summary**
   - Key factors influencing survival were identified.
   - Missing values were noted for future data cleaning.
   - Initial exploration provided a solid foundation for predictive modeling.

## Deliverables
- Jupyter Notebook (.ipynb file) with step-by-step code, graphs, and observations.
- PDF report summarizing the findings and visualizations.

## Conclusion
The exploratory data analysis revealed that survival chances on the Titanic were influenced primarily by gender, class, and fare. Handling missing data and outliers will be crucial for future predictive modeling tasks. This project sets the groundwork for further machine learning analysis and model building.


