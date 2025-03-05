# Data-Auto-Cleaner

AutoCleanData 📊✨ An automated data preprocessing and cleaning tool for various file formats, including CSV, Excel, JSON, SQLite, MySQL, PostgreSQL, and more.
Features 🚀
✔️ Supports multiple file formats (CSV, Excel, JSON, SQL, Parquet, etc.)
✔️ Handles missing values using KNN and Iterative Imputation
✔️ Detects and removes duplicate entries
✔️ Encodes categorical variables using Label Encoding
✔️ Saves cleaned and encoded datasets in multiple formats

How It Works ⚡
1️⃣ Load a dataset by providing its path
2️⃣ Perform an initial data analysis (missing values, total entries, etc.)
3️⃣ Automatically clean and preprocess the data
4️⃣ Save the cleaned and encoded dataset in a preferred format

Installation & Usage 🛠️
from auto_clean_data import Auto_Clean_Data

cleaner = Auto_Clean_Data("dataset.csv")
data = cleaner.read_file()
cleaned_data, encoded_data = cleaner.clean_data()
cleaner.save_data("output_directory/")

Dependencies 🏗️
pandas
numpy
scikit-learn
matplotlib
sqlite3, pymysql, psycopg2 (for database support)

Contributions 🤝
Feel free to contribute, report issues, or suggest improvements!
