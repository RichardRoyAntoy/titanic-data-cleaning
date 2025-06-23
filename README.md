🧠 AI & ML Internship – Task 1  
🚀 Task Title: Data Cleaning & Preprocessing  

---

📌 Objective: 
To learn and apply essential data cleaning and preprocessing techniques on a real-world dataset in preparation for machine learning tasks.

---

📂 Dataset Used:  
Titanic Dataset (`Titanic-Dataset(3).csv`)  
Contains passenger details including demographics, ticket info, and survival status from the Titanic ship disaster.

---

🛠️ Tools & Libraries Used:  
- Jupyter Notebook  
- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Scikit-learn  

---

✅ Steps Performed:

1. Imported Required Libraries  
Used Python libraries like `pandas`, `numpy`, `seaborn`, `matplotlib`, and `StandardScaler` from `sklearn`.

2. Loaded and Explored the Dataset  
Viewed basic dataset structure, column types, and counted missing values.

3. Handled Missing Values  
- Filled `Age` with median  
- Filled `Embarked` with mode  
- Dropped the `Cabin`, `Name`, and `Ticket` columns  
- Ensured no remaining null values

4. Encoded Categorical Features  
- Converted `Sex` using Label Encoding  
- Applied One-Hot Encoding to `Embarked`

5. Normalized / Standardized Numerical Columns  
- Scaled `Age` and `Fare` using `StandardScaler`

6. Visualized & Removed Outliers  
- Used boxplots to detect outliers  
- Removed extreme `Fare` values (based on IQR)

---

📊 Final Dataset Summary:  
- Cleaned dataset shape: `(after outlier removal)`  
- All features are numeric  
- Ready for machine learning models

---

🎯 Outcome / What I Learned:  
- How to identify and treat missing values  
- Applied `fillna()`, `drop()`, and median/mode techniques  
- Encoded categorical variables for model compatibility  
- Scaled features using `StandardScaler`  
- Detected and removed outliers with boxplots  
- Prepared a clean dataset suitable for ML modeling

---

📁 How to Run:  
- Open `Titanic_Preprocessing.ipynb` in Jupyter Notebook  
- Place `Titanic-Dataset.csv` in the same folder  
- Run all the cells in order

---

👨‍💻 Author:  
Richard Roy  
AI & ML Internship Participant
