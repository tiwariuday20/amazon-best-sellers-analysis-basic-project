# amazon-best-sellers-analysis-basic-project
# 📚 Amazon Best Sellers Analysis

**Exploratory Data Analysis of Amazon's bestselling books from 2009 to 2019 using Python and Pandas.**

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Status](https://img.shields.io/badge/Project-Completed-success)](#)

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Objectives](#-objectives)
- [Dataset](#-dataset)
- [Technologies Used](#-technologies-used)
- [Analysis Performed](#-analysis-performed)
- [Project Structure](#-project-structure)
- [Installation and Usage](#-installation-and-usage)
- [Output Files](#-output-files)
- [Key Learnings](#-key-learnings)
- [Disclaimer](#-disclaimer)

---

## 🔍 Overview

This project explores historical Amazon bestselling-book data to understand patterns in author popularity, reader ratings, book prices, and genres.

Using **Pandas**, the dataset is loaded, inspected, cleaned, analyzed, and exported into summary CSV files.

## 🎯 Objectives

- Understand the dataset's structure and characteristics.
- Identify and remove duplicate records.
- Rename columns for improved readability.
- Find authors with the most bestseller entries.
- Compare average ratings for Fiction and Non Fiction.
- Export analysis results for further exploration.

## 📊 Dataset

The dataset contains **550 original records** covering bestselling books from 2009 to 2019.

| Column | Description |
|---|---|
| `Name` | Book title |
| `Author` | Author's name |
| `User Rating` | Amazon user rating |
| `Reviews` | Number of user reviews |
| `Price` | Book price in the dataset |
| `Year` | Year the book appeared on the list |
| `Genre` | Fiction or Non Fiction |

> Note: These records represent historical data, not current Amazon bestseller rankings. Check the dataset source and license before redistributing the CSV.

## 🛠️ Technologies Used

- **Python** — programming language
- **Pandas** — data manipulation and analysis
- **CSV** — tabular data storage and result export

## 📈 Analysis Performed

### 1. Data Exploration
- `df.head()` — preview the first five rows.
- `df.shape` — check the number of rows and columns.
- `df.columns` — inspect column names.
- `df.describe()` — generate descriptive statistics.

### 2. Data Cleaning
- Remove duplicate records.
- Rename columns for readability.
- Convert the `Price` column to a numeric data type.

### 3. Author Popularity
Use `value_counts()` to identify authors with the most entries in the bestseller dataset.

### 4. Ratings by Genre
Group records by genre and calculate the average user rating using `groupby()` and `mean()`.

### 5. Export Results
Save the top 10 authors and average genre ratings into separate CSV files.

## 📁 Project Structure

```text
amazon-best-sellers-analysis/
├── main.py
├── bestsellers.csv
├── requirements.txt
├── README.md
├── .gitignore
├── top_authors.csv
└── avg_rating_by_genre.csv
```

The two output CSV files are generated when the analysis script runs.

## 🚀 Installation and Usage

### Prerequisites
- Python installed
- Git (optional, for cloning the repository)

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/amazon-best-sellers-analysis.git
cd amazon-best-sellers-analysis
```

Replace `YOUR_USERNAME` with your GitHub username.

### Step 2: Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### Step 3: Add the Dataset

Place `bestsellers.csv` in the project root directory.

### Step 4: Run the Analysis

```bash
python main.py
```

The script prints the exploration results and analysis summaries and generates the output CSV files.

## 📤 Output Files

| File | Description |
|---|---|
| `top_authors.csv` | Top 10 authors by number of bestseller entries |
| `avg_rating_by_genre.csv` | Average user rating grouped by genre |

## 🧠 Key Learnings

Through this project, I practiced:

- Loading CSV datasets with Pandas.
- Exploring data using DataFrame methods.
- Cleaning records and renaming columns.
- Aggregating data with `value_counts()` and `groupby()`.
- Calculating summary statistics.
- Exporting analysis results to CSV files.

## ⚠️ Disclaimer

This project is intended for educational purposes. The analysis reflects the historical dataset provided and does not represent current Amazon bestseller rankings.

---

**If you found this project useful, feel free to explore the code and share feedback.**
