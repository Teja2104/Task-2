
\
**Original Source**: [Titanic-Dataset.csv]  
**Cleaned File**: `Titanic-Cleaned.csv`


- Removed columns with excessive missing or irrelevant information: `Cabin`, `Ticket`, `Name`
- Dropped rows with missing values in key features like `Age` and `Embarked`
- Reset index post-cleaning
 Exploratory Data Analysis (EDA)

### Summary Statistics
- Computed basic statistics: mean, median, standard deviation, etc.

### Visualizations
- Histograms for distribution of numeric features
- Boxplots to detect outliers
- Correlation matrix and pairplots for feature relationships

### Observations
- Identified patterns in survival rate across gender and class
- Detected outliers in `Fare`
- Observed strong correlation between `Pclass`, `Fare`, and `Survi
 Columns in Cleaned Dataset

- `PassengerId`: Unique ID
- `Survived`: 0 = No, 1 = Yes
- `Pclass`: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Sex`: Gender
- `Age`: Age in years
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Fare`: Ticket fare
- `Embarked`: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## How to Use

1. Clone this repo
2. Access `Titanic-Cleaned.csv` for modeling or further analysis
3. Use the Jupyter notebook or Python scripts (if added) for EDA and ML
