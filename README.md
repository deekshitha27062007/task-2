# task-2
Titanic Data Set
 AI & ML Internship – Task 2: Exploratory Data Analysis (EDA)

 Objective
The goal of this task was to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset. EDA helps us understand the structure, patterns, and relationships in the dataset using statistical summaries and data visualizations.

 Dataset
- Name: Titanic Dataset  
- Source: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File Used: `titanic.csv`

  Tools & Libraries
- Python (Google Colab)
- Pandas
- Matplotlib
- Seaborn

 🔍 Steps Performed

1. Loaded the Dataset
   - Used Pandas to read the CSV file.
   
2. Summary Statistics
   - `df.info()`, `df.describe()`, and `df.isnull().sum()` used to understand basic structure and missing data.

3. Data Cleaning
   - Filled missing `Age` values with the median.
   - Dropped `Cabin` column due to too many missing values.
   - Removed rows with remaining missing values.

4. Visualizations
   - Histograms for understanding distributions (e.g., Age, Fare).
   - Boxplots to detect outliers.
   - Correlation Heatmap to see relationships between numeric variables.
   - Pairplot to observe pairwise relationships.
   - Barplots to compare survival rates across gender and classes.

   Insights Gained
   - Females had a significantly higher survival rate than males.
   - Passengers in 1st class had a higher chance of survival.
   - Children also had better survival rates compared to adults.

Sample Graphs
- Age Distribution
- Boxplot of Age by Survival
- Heatmap of Feature Correlations
- Pairplot of Age, Fare, and Survival

 Output Files
- `cleaned_titanic.csv`: Cleaned version of the dataset after handling missing values.
Author-Deekshitha S



