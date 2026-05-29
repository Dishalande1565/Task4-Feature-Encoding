# Task 4: Feature Encoding & Scaling
## AI & ML Data Analytics Internship

## Objective
To convert categorical features into numerical formats
and bring all numerical features to a similar scale
for better model performance.

## Dataset Used
- Titanic Dataset
- 891 rows × 12 columns

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Files
- Task4_Feature_Encoding.ipynb → Main notebook

## Steps Performed
1. Identified Nominal vs Ordinal variables
2. Applied Label Encoding for Sex column
3. Applied One-Hot Encoding for Embarked column
4. Avoided Dummy Variable Trap using drop_first=True
5. Applied StandardScaler (Standardization)
6. Applied MinMaxScaler (Normalization)
7. Compared distributions before & after scaling

## Key Findings
- Sex: male=1, female=0 (Label Encoded)
- Embarked: 3 categories → 2 columns (One-Hot)
- Age: Standardized mean=0, std=1
- Fare: Normalized range 0 to 1
- Scaling is must for KNN & SVM algorithms ✅
