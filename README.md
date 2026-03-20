📊 Pandas Basics Notebook

This project is a beginner-friendly introduction to Pandas, a powerful Python library used for data analysis and manipulation.

🚀 What is Pandas?

Pandas is a Python library used for working with structured data (like tables).
It helps in:

Cleaning data

Analyzing data

Manipulating datasets

Exploring data

It is similar to working with Excel sheets or SQL tables.

⚙️ Installation
pip install pandas
📥 Importing Pandas
import pandas as pd

Check version:

pd.__version__
🧱 What is a DataFrame?

A DataFrame is a 2D table (rows & columns) used to store data.

🛠️ Creating DataFrames
1. Using a List
df = pd.DataFrame([11, 22, 33], columns=['Col_Name'])
2. Using Dictionary
data = {
    'Name': ['Madhav', 'Vishakha', 'Lalita', 'Rishabh'],
    'Age': [16, 17, 18, 19],
    'Salary': [90000, 70000, 50000, 30000]
}

df = pd.DataFrame(data)
🔍 Basic DataFrame Operations
df.head()        # First 5 rows
df.tail()        # Last 5 rows
df.shape         # (rows, columns)
df.columns       # Column names
df.info()        # Data info
✏️ Modifying Data
Rename Column
df.rename(columns={'Salary': 'Monthly_Salary'}, inplace=True)
📈 Key Topics Covered in Notebook

Creating DataFrames

Viewing and understanding data

Renaming columns

Data inspection (info, shape, head, tail)

Working with structured datasets

🎯 Purpose

This notebook is designed for:

Beginners learning Pandas

Students starting Data Science

Practice for real-world data handling

🧠 Future Improvements

You can extend this notebook by adding:

Data cleaning techniques

Handling missing values

GroupBy operations

Data visualization (Matplotlib / Seaborn)

🙌 Author

Created by Manik 🚀
