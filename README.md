# 📊 Task 2: Exploratory Data Analysis (EDA)

## 🧠 Objective
Perform Exploratory Data Analysis to gain insights into the Titanic dataset using statistics and visualizations.

## 🛠️ Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly

## 📂 Dataset
**Dataset Used**: Titanic Dataset  
**Download Link**: [Click here to download dataset](#)  
*(Update the link with actual file or source like [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data))*

---

## 🔍 Steps Performed

### 1. Load and Understand the Data
- Loaded the Titanic dataset using Pandas.
- Inspected data types and missing values using `.info()` and `.isnull().sum()`.

### 2. Summary Statistics
- Used `.describe()` to generate mean, median, standard deviation, etc.
- Counted missing values for each column.

### 3. Visualizations
#### a. Histograms & Boxplots
- Histograms for distributions of numeric features like Age, Fare.
- Boxplots to detect outliers in numerical data.

#### b. Correlation & Relationships
- Pairplot for Age, Fare, and Pclass colored by Survival.
- Heatmap for correlation matrix.

#### c. Categorical Analysis
- Countplots of `Sex` and `Pclass` vs `Survived`.
- KDE plots for Age distribution by survival status.

#### d. Interactive Visualizations (Plotly)
- Scatter plot of Age vs Fare colored by survival.
- Boxplot of Fare across Pclass.

---

## 🧠 Key Inferences
- Women had significantly higher survival rates than men.
- Passengers in 1st class had better survival odds than those in 2nd or 3rd.
- Children under 10 showed higher survival chances.
- Passengers who paid higher fares had better survival probabilities.

---

## 💻 How to Run
1. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn plotly
