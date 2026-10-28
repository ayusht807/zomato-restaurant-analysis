# Zomato Restaurant Data Analysis

## Project Overview
This project analyzes restaurant data from Bangalore using Python, Pandas, Matplotlib, and Seaborn. The goal is to identify patterns in restaurant types, cuisines, ratings, pricing, online ordering, and table booking.

## Objectives
- Clean and prepare restaurant data for analysis.
- Explore restaurant types and popular cuisines.
- Analyze restaurant ratings and approximate cost.
- Compare ratings by online ordering and table booking availability.
- Identify highly rated locations and communicate findings through visualizations.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The dataset contains 51,717 restaurant records and 17 columns, including restaurant names, locations, cuisines, ratings, votes, online ordering, table booking, and approximate cost for two people.

## Key Findings
- Quick Bites was the most common restaurant type, with 19,132 listings.
- North Indian cuisine appeared most frequently, followed by Chinese.
- Restaurants offering online ordering had an average rating of 3.72, compared with 3.66 for those without it.
- Restaurants offering table booking had an average rating of 4.14, compared with 3.62 for those without it.
- Average ratings increased across the cost groups in this analysis, from 3.57 for budget restaurants to 4.13 for luxury restaurants.
- Lavelle Road had the highest average rating (4.14) among locations with at least 100 rated records.

These findings describe associations in this dataset and do not establish cause and effect.

## Project Structure
```text
zomato-restaurant-analysis/
├── data/
│   ├── zomato.csv
│   └── zomato_cleaned.csv
├── images/
├── zomato_analysis.ipynb
├── README.md
└── requirements.txt
```

## How to Run
1. Clone or download this repository.
2. Install the required libraries:
   `pip install -r requirements.txt`
3. Open `zomato_analysis.ipynb` in Jupyter Notebook or VS Code.
4. Run the notebook cells in order.

## Skills Demonstrated
- Data cleaning and preprocessing
- Exploratory data analysis
- Missing-value handling
- Grouping and aggregation with Pandas
- Data visualization
- Business insight generation

## Conclusion
This project demonstrates how restaurant data can be cleaned, explored, and visualized to understand patterns in customer ratings, cuisine popularity, pricing, and restaurant services.
