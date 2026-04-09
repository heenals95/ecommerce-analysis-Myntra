# Myntra Fashion Data Analysis

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-lightgrey)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-teal)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

This project presents an exploratory data analysis of a Myntra fashion dataset using Python, pandas, matplotlib, and seaborn.

The notebook focuses on turning raw product data into business insights by analyzing:
- brand performance
- pricing patterns
- discount behavior
- customer ratings
- product segmentation

## Project Overview

The analysis is designed as a beginner-friendly portfolio project and follows a practical business style. It starts with data cleaning and feature engineering, then moves into visual analysis and business recommendations.

The main objective is to answer questions such as:
- Which brands dominate the catalog?
- Which price segments appear strongest?
- How are discounts used across products?
- Do higher prices lead to higher ratings?
- What actions could a business take from these findings?

## Key Business Insights

- A small group of brands contributes a large share of product listings, which suggests strong assortment concentration.
- Medium and High price segments appear to be the most commercially important parts of the catalog.
- Discounting is heavier in lower price bands, while premium products are discounted more carefully.
- Customer ratings remain relatively stable across price ranges, so higher price does not automatically mean better reviews.
- Premium products show a wider price spread and more extreme outliers, which suggests a more varied product mix in that segment.

## Project Structure

```text
Python Poject/
|-- data/
|   `-- myntra_dataset_ByScraping.csv
|-- notebooks/
|   `-- analysis.ipynb
|-- requirements.txt
`-- README.md
```

## Tech Stack

- Python
- pandas
- numpy
- matplotlib
- seaborn
- jupyter
- ipykernel

## Dataset Features

The dataset includes these important columns:
- `brand_name`
- `pants_description`
- `price`
- `MRP`
- `discount_percent`
- `ratings`
- `number_of_ratings`

## Analysis Covered

The notebook includes:
- data loading
- data cleaning
- feature engineering
- univariate analysis
- bivariate analysis
- multivariate analysis
- outlier detection
- business recommendations

Some of the visual and business analysis sections include:
- top brands by product count
- revenue potential by price category
- discount distribution
- price vs ratings analysis
- brand vs ratings comparison
- correlation analysis
- final business recommendations

## How To Run This Project

### 1. Open The Project Folder

```powershell
cd "C:\Users\heena\repos\Python Poject"
```

### 2. Activate The Virtual Environment

If you are using PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

If you are using Command Prompt:

```cmd
.venv\Scripts\activate
```

### 3. Install Dependencies

```powershell
pip install -r requirements.txt
```

### 4. Open The Notebook

Open the notebook below and run the cells in order:

```text
notebooks/analysis.ipynb
```

## Key Skills Demonstrated

This project demonstrates practical data analysis skills such as:
- reading CSV files with pandas
- cleaning missing and duplicate data
- creating new features from existing columns
- building charts using matplotlib and seaborn
- interpreting business insights from visualizations

## Example Insights

Some high-level patterns observed in the notebook include:
- a few brands contribute a large share of product listings
- medium and high price ranges are important commercial segments
- discounting is more aggressive in lower price bands
- ratings do not show a strong direct relationship with price
- premium products show wider price variation and more outliers

## Notes

- The notebook uses the relative path `../data/myntra_dataset_ByScraping.csv` to load the dataset
- `PriceCategory` is a generated feature used for segmentation
- `DiscountPercent` is a generated feature used to analyze promotional strategy

## Author

Heenal S.
