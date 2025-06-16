TASK2

🛠 Titanic Dataset – Data Cleaning & Exploratory Data Analysis (EDA)
📂 Dataset Used
Path: /content/Titanic-Dataset.csv
Rows: 891
Columns: 12

🧹 Data Cleaning Steps
Handled Missing Values:

Age: Filled with median value.

Embarked: Filled with mode.

Cabin: Dropped due to excessive missing values.

Type Conversion:

Converted Pclass, Sex, and Embarked to categorical types.

📊 Exploratory Data Analysis (EDA)
1. 🚢 Survival Count
Bar chart showing how many passengers survived vs. not survived.

2. 👨‍👩‍👧 Survival by Sex
More females survived compared to males.

3. 🎟 Survival by Passenger Class
First-class passengers had a higher survival rate than 2nd and 3rd class.

4. 📈 Age Distribution by Survival
Kernel density plots (KDE) show:

Survivors were often younger.

Few infants and elderly survived.

5. 💰 Fare Distribution by Survival
Survivors paid higher fares on average.

KDE plot shows a clear right-skewed distribution for survivors.

6. 🔥 Correlation Heatmap
Positive correlation between:

Fare and Survived

Parch, SibSp and Survived (mild)

Negative correlation between Age and Survived.

✅ Key Takeaways
Sex and Pclass are strong indicators of survival.

Younger passengers and those with higher fare tickets had better chances.

KDE and count plots provide clear visual understanding.
