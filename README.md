🏝 Travel Triangle EDA Project
📌 Project Overview
- This project involves web scraping travel package data from TravelTriangle and performing Exploratory Data Analysis (EDA) to understand pricing trends, discounts, destinations, and package highlights.
The goal is to extract structured data from multiple categories such as Family, Adventure, and Beach tour packages, clean and analyze it, and present insights for travel market understanding.

📊 Features
- Web Scraping: Automated extraction of travel package details using requests and BeautifulSoup.

- Data Cleaning: Removing duplicates, handling missing values, and standardizing formats.

- Exploratory Data Analysis:

- Price distribution analysis

- Discount trends

- Popular destinations

- Duration vs. price comparison

- Multi-category scraping: Family, Adventure, and Beach packages.

🛠 Tech Stack
- Python 🐍

- Libraries:

requests – Fetching HTML content

BeautifulSoup – Parsing HTML

pandas – Data storage, cleaning, and analysis

- matplotlib & seaborn – Visualization

- 📂 Dataset
- The dataset contains:

1.Package Title

2.Duration

3.Discount %

4.Discounted Price

5.Original Price

6.Location

7.Highlights

8.Source Category

- 📏 Size: ~500+ rows (from 3 package categories × multiple pages)

- 🔍 Steps Performed
Data Collection

- Scraped up to 8 pages for each travel theme (Family, Adventure, Beach).

- Extracted titles, durations, discounts, prices, locations, and highlights.

- Data Cleaning

- Removed duplicates

- Converted prices to numerical format

- Standardized durations

- Exploratory Data Analysis

- Price and discount distribution

- Most visited destinations

- Relationship between package duration and cost

- Visualization

- Bar charts for top destinations

- Price vs. Duration scatter plots

- Discount % distribution plots

- 📈 Insights
- Certain destinations consistently offer higher discounts.

- Longer durations generally correlate with higher prices, but exceptions exist.

- Beach packages showed more seasonal discounts compared to Family packages.


