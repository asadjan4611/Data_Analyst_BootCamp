# 📊 Data Analyst BootCamp

> A comprehensive collection of hands-on data analysis exercises and projects using Python, Pandas, and Jupyter Notebooks.

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Latest-green.svg)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 🎯 Overview

This repository contains a structured learning path for aspiring data analysts, covering fundamental to advanced data manipulation, cleaning, and analysis techniques. Each activity builds upon previous concepts, providing a progressive learning experience.

## 📚 Repository Structure

```
Data_Analyst_BootCamp/
│
├── 📓 Activity Notebooks
│   ├── Activity_1.ipynb          # Python fundamentals & basic operations
│   ├── 2nd_Activty.ipynb         # Data types, lists, tuples, and DataFrames
│   └── Lab3.ipynb               # Conditional logic and data type operations
│   ├── Activity_4.ipynb          # Data exploration with Iris dataset
│   ├── Activity_6 (1).ipynb      # Data cleaning and missing value handling
│   ├── Activity_7.ipynb          # Working with multiple datasets (Netflix, Spotify, etc.)
│   ├── Activity_8.ipynb          # Advanced data cleaning and preprocessing
│   ├── Activty_11.ipynb         # Data organization: sorting, filtering, slicing
│   ├── Activty_12.ipynb         # Advanced data manipulation with multiple datasets

│
├── 📁 Sample Datasets
│   ├── netflix_sample.csv
│   ├── online_retail_sample.csv
│   ├── sales_data2.csv
│   ├── spotify_sample.csv
│   ├── superstore_sample.csv
│   ├── train_and_test2.csv
│   └── world_population_sample.csv
│
└── 📄 Documentation
    └── Student_Quick_Reference.md
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- Basic understanding of Python syntax

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/asadjan4611/Data_Analyst_BootCamp.git
   cd Data_Analyst_BootCamp
   ```

2. **Install required packages**
   ```bash
   pip install pandas numpy seaborn openpyxl jupyter
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

---

## 📖 Activities Breakdown

### 🔹 Activity 1: Python Fundamentals
- Basic Python operations
- Working with lists and tuples
- Introduction to Pandas DataFrames
- Data manipulation basics

### 🔹 Activity 2: Data Structures
- Lists, tuples, and dictionaries
- Creating and manipulating DataFrames
- Column operations and renaming
- Data filtering and merging

 ### 🔹 Lab 3: Conditional Logic & Data Types
- Boolean operations
- Conditional statements
- Date and time operations
- String manipulation
- Working with different data types

### 🔹 Activity 4: Data Exploration
- Loading and exploring datasets (Iris dataset)
- Data inspection techniques (`head()`, `info()`, `describe()`)
- Working with JSON data
- File system operations

### 🔹 Activity 6: Data Cleaning
- Handling missing values
- Filling null values with mean/median
- Dropping rows and columns
- Data quality assessment

### 🔹 Activity 7: Multi-Dataset Operations
- Working with Netflix, Spotify, Superstore datasets
- Missing value detection and removal
- Data filtering and aggregation
- Exporting data to various formats (CSV, Excel, JSON, XML)
- ETL pipeline basics

### 🔹 Activity 8: Advanced Data Cleaning
- String manipulation and cleaning
- Removing special characters
- Case standardization
- Email validation
- Outlier detection and treatment
- Data type conversion

### 🔹 Activity 11: Data Organization
- Sorting data (single and multiple columns)
- Filtering with conditions
- Slicing data (`iloc` vs `loc`)
- Transposing and pivoting
- Appending and concatenating datasets
- Truncating data

### 🔹 Activity 12: Advanced Data Manipulation
- Working with Iris, Tips, and Flights datasets
- Complex sorting and filtering operations
- Data slicing and transposition
- Appending and truncating operations
- Multi-dataset workflows



---

## 🛠️ Key Skills Covered

- ✅ **Data Loading**: Reading CSV, Excel, and JSON files
- ✅ **Data Exploration**: Understanding dataset structure and statistics
- ✅ **Data Cleaning**: Handling missing values, duplicates, and outliers
- ✅ **Data Transformation**: Sorting, filtering, grouping, and aggregating
- ✅ **Data Manipulation**: Merging, concatenating, and reshaping data
- ✅ **Data Export**: Saving processed data in multiple formats
- ✅ **String Operations**: Cleaning and standardizing text data
- ✅ **Data Validation**: Email validation, data type conversion

---

## 📊 Datasets Used

| Dataset | Description | Use Case |
|---------|-------------|----------|
| **Iris** | Classic classification dataset | Data exploration and manipulation |
| **Tips** | Restaurant tipping data | Aggregation and grouping exercises |
| **Flights** | Airline passenger data | Time series and sorting operations |
| **Netflix** | Movie/show catalog | Missing value handling |
| **Spotify** | Music popularity data | Data transformation |
| **Superstore** | Sales transaction data | Filtering and aggregation |
| **Sales Data** | E-commerce transactions | Advanced cleaning and preprocessing |

---

## 💡 Learning Path

1. **Beginner** → Start with `Activity_1.ipynb` and `2nd_Activty.ipynb`
2. **Intermediate** → Progress to `Activity_4.ipynb`, `Activity_6`, and `Activity_7`
3. **Advanced** → Master `Activity_8`, `Activty_11`, and `Activty_12`

---

## 🎓 Best Practices Demonstrated

- **Code Organization**: Clean, well-commented code
- **Data Validation**: Checking data quality before processing
- **Error Handling**: Graceful handling of missing data
- **Documentation**: Clear explanations and markdown cells
- **Reproducibility**: Consistent data processing workflows

---

## 📝 Usage Example

```python
import pandas as pd
import numpy as np

# Load dataset
df = pd.read_csv('sales_data2.csv')

# Explore data
print(df.head())
print(df.info())

# Clean data
df = df.dropna()
df['Customer_Name'] = df['Customer_Name'].str.strip()
df['City'] = df['City'].str.title()

# Analyze
print(df.describe())
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/asadjan4611/Data_Analyst_BootCamp/issues).

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Asad Jan**

- GitHub: [@asadjan4611](https://github.com/asadjan4611)
- Repository: [Data_Analyst_BootCamp](https://github.com/asadjan4611/Data_Analyst_BootCamp)

---

## 🙏 Acknowledgments

- Pandas documentation team
- Seaborn for providing sample datasets
- Jupyter project for the excellent notebook environment

---

## 📈 Future Enhancements

- [ ] Add data visualization exercises
- [ ] Include machine learning basics
- [ ] Add SQL integration examples
- [ ] Create video tutorials
- [ ] Add more real-world datasets

---

<div align="center">

**⭐ If you find this repository helpful, please consider giving it a star! ⭐**

Made with ❤️ for the data analysis community

</div>


