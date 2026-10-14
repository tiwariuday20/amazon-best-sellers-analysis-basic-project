# amazon-best-sellers-analysis-basic-project
Exploratory data analysis of Amazon bestselling books using Python and Pandas.

Amazon Best Sellers Analysis

Overview

A beginner-friendly data analysis project using Python and Pandas to explore Amazon's bestselling books from 2009 to 2019.

Objectives

Explore the dataset and understand its structure.

Clean duplicate records and rename columns.

Identify authors with the most bestselling-book entries.

Compare average reader ratings across Fiction and Non Fiction.

Export analysis results to CSV files.

Technologies Used

Python

Pandas

CSV

Dataset

The dataset contains information about bestselling books, including:

Book title

Author

User rating

Number of reviews

Price

Year

Genre

The dataset contains 550 records in its original form. Please refer to the dataset's source and license before redistributing it.

How to Run

Clone or download this repository.

Install dependencies:

python -m pip install -r requirements.txt

Place bestsellers.csv in the project folder.

Run:

python main.py

Analysis Performed

Dataset exploration using head(), shape, columns, and describe().

Duplicate removal and column renaming.

Author popularity analysis using value_counts().

Average ratings by genre using groupby() and mean().

Export of the top 10 authors and genre rating summaries.

Outputs

top_authors.csv

avg_rating_by_genre.csv

Learning Outcomes

This project demonstrates foundational skills in data loading, data cleaning, aggregation, descriptive statistics, and exporting results with Pandas.

Disclaimer

This is an educational data analysis project. The results describe the supplied historical dataset and do not represent current Amazon bestseller rankings.
