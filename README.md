# 🚀 Internship Task 1: Titanic Dataset - Data Preprocessing

### 🎯 Objective:
Clean and prepare the Titanic dataset for machine learning.

---

### ✅ Steps Completed:

1. **Imported and explored the dataset**
   - Viewed null values, data types, and overall structure using `info()` and `describe()`.

2. **Handled missing values**
   - Filled `Age` and `Fare` with their **mean**.
   - Filled `Embarked` and `Cabin` using **mode**.

3. **Converted categorical features into numerical**
   - Applied **Label Encoding** and **One-Hot Encoding** for:
     - `Sex`
     - `Embarked`
     - `Pclass`
     - `Title` (extracted from `Name`)

4. **Normalized / Standardized numerical features**
   - Applied **z-score normalization** to `Age` and `Fare` columns.

5. **Visualized and removed outliers**
   - Used **boxplots** to detect outliers.
   - Removed them using the **IQR method**.


