# ✈️ British Airways Customer Review Analysis

This project focuses on scraping, analyzing, and visualizing customer reviews of British Airways to uncover key insights about traveler experiences, satisfaction levels, and service quality.

## 🧰 Tools & Technologies Used
- **Python**: Web scraping with `BeautifulSoup` and `requests`, data manipulation with `pandas`
- **NLTK**: Sentiment analysis using the VADER lexicon
- **Excel**: Data cleaning, aggregation, and visualization

## 📊 Project Objectives
- Extract review data from the [Skytrax website](https://www.airlinequality.com/airline-reviews/british-airways)
- Analyze customer sentiment and identify trends across traveler types, seat classes, and trip verification status
- Visualize findings using Excel charts and pivot tables

## 🔍 Key Insights
- Only **35%** of reviewers would recommend British Airways
- Negative sentiment is significantly more common in **non-verified** reviews
- **Solo leisure** travelers were the most common group
- **Business class** had the highest review volume among seat types

## 📁 Project Structure
```
├── web_scraping_ba_reviews.py   # Python script for scraping reviews
├── sentiment_analysis.py        # VADER sentiment analysis logic
├── british_airways_reviews.csv  # Final cleaned dataset (3900+ reviews)
├── excel_visualizations.xlsx    # Charts, pivot tables, and insights
└── README.md                    # Project documentation
```

## 🚀 Getting Started

### Prerequisites
Install the required Python libraries:
```bash
pip install requests beautifulsoup4 pandas nltk
```

### Run the scraper
```python
python web_scraping_ba_reviews.py
```

### Run sentiment analysis
```python
python sentiment_analysis.py
```

### Visualize the Data
Open the `excel` file to explore charts and insights.

## 🤝 Contributions
Pull requests are welcome! If you find any issues or have suggestions, feel free to open an issue or submit a PR.
