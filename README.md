# fictional-octo-sporksql
🎬 IMDb Movie Review Analysis with SQL on Google Colab

Project Type: Data Analysis / SQL
Tools Used: Python, Pandas, SQLite, SQL, Google Colab
Dataset: IMDb Large Movie Review Dataset (25,000 labeled reviews)

Project Aim:

To explore and analyze movie review sentiments using SQL inside Google Colab. The goal was to uncover patterns in word usage, review length, and label reliability between positive and negative reviews.

Key Steps:

1. **DATA EXTRACTION**
   
   Extracted and preprocessed 25,000 .txt files from .tar.gz.
   Split into positive and negative folders.
3. **DATA PREPARATION**
   
   Read each review from 'pos/' and 'neg/' folders.
   Labeled them as 'positive' or 'negative'.
   Combined them into a single Pandas DataFrame.
5. **LOAD INTO SQLite**
   
   Created a SQLite database 'imdb_reviews.db'.
   Stored the reviews as a table named 'reviews'.
7. **SQL ANALYSIS**
   
   Wrote over 15 SQL queries to:
   Calculate average review lengths.
   Track most common words by sentiment.
   Used SQL 'CASE' statements to group reviews into short/medium/long.
   Detect contradictions in sentiment labels.
   Use window functions to rank word frequencies.
9. **VISUALIZATION**
    
   Visualized review length distribution in Python

Highlights:

Used SQL CASE, LIKE, GROUP BY, and ROW_NUMBER() functions.

Built a basic keyword-based sentiment scoring logic.

Identified mislabeled reviews based on word context.

Built a foundation for future ML-based sentiment modeling.


Outcome:

The project reveals valuable insights about sentiment distribution, labeling consistency, and writing patterns — and prepares the dataset for future machine learning work.
