# Netflix Content Analysis

## Overview
This project analyzes Netflix's content catalog (movies and TV shows) to understand how the platform's content strategy has evolved over time, which genres and countries dominate, and where Netflix has opportunities for future growth.

## Objectives
- Analyze content trends to provide strategic recommendations
- Understand how genres and audience preferences affect Netflix's growth
- Study country-wise content contributions across Netflix's international audience

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly

## Data Cleaning & Preprocessing
- Converted `Release Date` to datetime format
- Handled missing values in `Director`, `Cast`, and `Country` (filled with "Unknown" or mode)
- Removed duplicate records
- Checked for outliers across relevant fields

## Key Analysis & Insights
- **Content growth over time:** TV Shows have consistently been popular on Netflix, while Movies saw a sharp rise in popularity starting around 2014.
- **Top genres:** International Movies, Dramas, and Comedies are the most dominant genres on the platform.
- **Top content-producing countries:** United States, India, United Kingdom, Japan, and South Korea show the highest content growth.
- **Regional preferences:** Genre popularity varies significantly by country — for example, Indian audiences favor international movies, dramas, and comedy, while the US leans toward dramas, comedy, and documentaries.
- **Ratings by region:** Content ratings differ by country, reflecting differing audience/parental caution norms (e.g., TV-14 is more common in India).
- **Growth opportunities:** Romantic movies, classic movies, and reality TV showed the strongest growth potential; comedies in India, international movies in the US, and thrillers in India stood out as high-opportunity segments.

## Conclusion
The analysis surfaces actionable insights into Netflix's content strategy — highlighting which genres, regions, and content types Netflix should prioritize to sustain growth and better serve its global audience.

## How to Run
1. Clone this repository
2. Install dependencies: `pip install pandas numpy matplotlib seaborn plotly`
3. Place `Netflix Dataset.csv` in the project directory
4. Run the notebook: `Netflix_data_analysis.ipynb`
