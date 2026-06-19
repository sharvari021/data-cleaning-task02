# Task 02 — Data Cleaning and Preparation

## 📌 Objective
Load a real-world dataset (Global Superstore) and perform data cleaning 
and preparation using Python and Pandas library.

---

## 🛠️ Tools & Technologies
- Python 3
- Pandas
- Google Colab
- Git & GitHub

---

## 📂 Dataset
- **Name:** Global Superstore Dataset
- **Format:** CSV
- **Records:** 9994 rows × 21 columns

---

## ✅ Steps Performed

### 1. Load Dataset
- Loaded the Global Superstore CSV file into a Pandas DataFrame

### 2. Explore Data
- Checked dataset shape, column names and data types
- Identified missing values
- Identified duplicate rows

### 3. Handle Missing Values
- Filled numeric columns with median values
- Filled categorical columns with mode values

### 4. Drop Duplicates
- Detected and removed duplicate rows from the dataset

### 5. Convert Data Types
- Converted `Order Date` column from string to datetime format
- Converted `Ship Date` column from string to datetime format

### 6. Export Cleaned Data
- Saved the cleaned dataset as `superstore_cleaned.csv`

---

## 🚀 How to Run

1. Open `Task02_Data_Cleaning.ipynb` in Google Colab
2. Upload `superstore_raw.csv` to Colab
3. Run all cells in order
4. Cleaned file will be saved as `superstore_cleaned.csv`

---

