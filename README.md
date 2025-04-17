# SCREEN_TIME_PROJECT

# 📊 Screen Time Data ECT Project

This project demonstrates an end-to-end ETL (Extract,Cleanse, Transform) pipeline on children's screen time data. It uses Python libraries like `pandas` and `numpy` to clean and engineer features that are ready to be stored in a Data Warehouse.

---

## 🧠 Project Objective

To extract, clean, and transform average daily screen time data for children and prepare it for analytical or warehousing purposes.

---

## 📂 Files Included

| File Name                     | Description |
|------------------------------|-------------|
| `screen_time.csv`            | The raw dataset downloaded from Kaggle |
| `extract_clean_transform.ipynb` | Jupyter notebook that performs ETL operations |

---

## 🔧 Technologies Used

- Python
- Jupyter Notebook
- pandas
- numpy

---

## 🔄 ECT Process

### 1. **Extract**
- Loaded the CSV dataset using pandas.

### 2. **Cleanse**
- Checked for missing values
- Removed invalid entries (e.g., negative screen time)

### 3. **Transform**
- Encoded categorical columns (e.g., Gender → Gender_Code)
- Created `Is_Weekend` column
- Normalized the screen time values

---

## 📈 Engineered Features

- `Gender_Code`: Numeric encoding of gender
- `Is_Weekend`: Binary flag for weekend days
- `Normalized_Screen_Time`: Scaled version of screen time for ML readiness

---

## 🚀 Future Scope

- Load the transformed dataset into a cloud-based Data Warehouse
- Build dashboards or run analytical queries
- Extend to predictive modeling

---

## 📎 Source

Dataset from Kaggle:  
[Average Daily Screen Time for Children](https://www.kaggle.com/datasets/ak0212/average-daily-screen-time-for-children)

---
