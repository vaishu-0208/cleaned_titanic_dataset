# cleaned_titanic_dataset
Key Tasks Performed
Data Cleaning
Loaded the Titanic dataset from a CSV file.

Filled missing values:

Age: forward fill.

Cabin: backward fill.

Embarked: forward fill.

Removed duplicate entries.

Outlier Detection
Used IQR method to remove outliers from the Fare column.

Visualized before and after using boxplots.

Exploratory Data Analysis
Count plots for Sex, Survived (with hue by sex), AgeCategory, and Embarked.

Used seaborn and matplotlib for visualizations.

Feature Engineering
Converted Sex column to numeric using LabelEncoder.

Created a new categorical feature AgeCategory:

Minor (age < 18)

Major (18 ≤ age < 60)

Senior Citizen (age ≥ 60)
