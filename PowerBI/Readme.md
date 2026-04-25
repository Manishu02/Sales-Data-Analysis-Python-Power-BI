# 🐍 Data Cleaning Process (Python)

This section explains how raw sales data was transformed into a clean dataset for analysis.

---

## 🔧 Steps Performed

### 1. Data Loading
Loaded dataset using pandas.

### 2. Column Cleaning
Removed extra spaces from column names.

### 3. Data Type Conversion
- Converted ORDERDATE to datetime  
- Converted SALES to numeric  

### 4. Missing Value Handling
Filled missing values in:
- ADDRESSLINE2  
- STATE  
- TERRITORY  
- POSTALCODE  

### 5. Feature Engineering
Extracted:
- Year  
- Month  

### 6. Data Validation
- Checked missing values  
- Checked duplicate records  

---

## 📂 Output
Clean dataset exported as:
`clean_sales_data.csv`
