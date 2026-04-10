# TV Brands Market Analysis | Exploratory Data Analysis (EDA)

---

## Project Overview

TV Brands Market Analysis | EDA project using Python | Analyzing price, screen size, resolution, ratings & brand trends from Kaggle dataset.

This project performs a comprehensive Exploratory Data Analysis (EDA) on TV brands market data. The goal is to uncover meaningful patterns and insights about TV pricing, brand popularity, customer ratings, features, and market trends using Python-based data analysis and visualization techniques.

---

## Dataset

- Source: Kaggle — TV Brands Market Dataset
- Format: CSV

| Column | Description |
|---|---|
| Brand | TV manufacturer/brand name |
| Model | TV model name |
| Price | Price in local/USD currency |
| Screen Size | Display size in inches |
| Resolution | Display resolution (HD, FHD, 4K, 8K) |
| Rating | Customer rating (out of 5) |
| Reviews | Number of customer reviews |
| Display Type | LED, OLED, QLED, etc. |
| Smart TV | Whether the TV is a Smart TV |
| OS | Operating system (Android, Tizen, WebOS, etc.) |

---

## Objectives

- Understand the distribution of TV brands in the market
- Analyze pricing trends across brands and features
- Explore the relationship between screen size, resolution, and price
- Identify top-rated brands and models
- Discover correlations between features and customer satisfaction
- Visualize market share and competitive landscape

---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python 3.8+ | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Matplotlib | Static data visualizations |
| Seaborn | Statistical data visualization |
| Jupyter Notebook | Development environment |

---

## Key Analysis Performed

### 1. Data Overview
- Shape, data types, missing values
- Basic statistical summary

### 2. Data Cleaning
- Handling null/missing values
- Removing duplicates
- Data type conversions
- Outlier detection

### 3. Univariate Analysis
- Distribution of prices
- Brand frequency/market share
- Rating distribution

### 4. Bivariate Analysis
- Price vs Screen Size
- Brand vs Average Rating
- Resolution vs Price

### 5. Correlation Analysis
- Heatmap of feature correlations
- Feature impact on pricing

### 6. Insights & Findings
- Most popular brands by volume
- Best value-for-money TVs
- Premium vs budget segment analysis

---

## How to Run

1. Clone the repository
2. Install dependencies: pip install -r requirements.txt
3. Download the dataset from Kaggle and place it in the data/ folder
4. Open the notebook: jupyter notebook notebooks/tv_eda_analysis.ipynb

---

## Project Structure

tv-brand-market-analysis/
├── data/
│   └── tv_brands_dataset.csv
├── notebooks/
│   └── tv_eda_analysis.ipynb
├── images/
└── README.md

---

## Key Insights

- Brand X dominates the market with the highest number of listings
- 4K TVs are priced significantly higher than FHD models on average
- Budget brands show surprisingly competitive customer ratings
- Larger screen sizes do not always correlate with higher ratings



