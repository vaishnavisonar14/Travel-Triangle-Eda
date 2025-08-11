# Travel-Triangle-Eda
Travel Triangle EDA
📌 Project Overview
This project performs web scraping and Exploratory Data Analysis (EDA) on travel packages from Travel Triangle, a tourism booking platform.
The goal is to scrape travel package details, clean and process the data, detect anomalies, and analyze pricing and package trends.

🔍 Project Steps
1. Web Scraping
Used Python with requests and BeautifulSoup to scrape multiple pages of travel package data.

Extracted:

Package Title

Duration

Discount

Discounted Price

Original Price

Location

Highlights

Implemented pagination to scrape up to 8 pages of results.

2. Data Cleaning
Converted extracted lists into a Pandas DataFrame.

Removed null/missing values.

Corrected data types for numeric columns.

Removed duplicates.

3. Outlier Detection
Identified unusually high standard deviation in:

Discount Price

Original Price

Amount Saved

Detected negative values in “Amount Saved” (likely incorrect).

4. Exploratory Data Analysis
Generated descriptive statistics (mean, median, min, max).

Visualized distributions of prices and discounts.

Compared original vs discounted prices.

Analyzed top locations and popular durations.

🛠 Tools & Libraries
Python (Jupyter Notebook)

requests, BeautifulSoup — web scraping

pandas, numpy — data cleaning & analysis

matplotlib, seaborn — visualization

📈 Key Insights
Some packages had negative savings due to data inconsistencies.

Price distributions showed high variability — likely due to different package types.

Certain destinations appeared more frequently, showing higher popularity.

