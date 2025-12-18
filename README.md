🦄 Unicorns Cleaning & Validation
Project Overview
This project focuses on cleaning and validating a dataset of global unicorn companies (private companies valued at $1B+). The goal is to ensure the data is accurate, consistent, and ready for further analysis or modeling.
The dataset includes information such as:
Company name
Valuation (in billions USD)
Continent and country/region
Industry
Top investors

Objectives
Remove duplicate company entries
Filter for unicorns with valuation ≥ $1B
Focus on companies backed by top investors: Sequoia Capital, Tiger Global Management, and Accel
Validate missing or inconsistent data
Encode categorical variables for analysis

Key Steps
Data Cleaning
Removed duplicate companies
Handled missing values in critical columns (Valuation, Top Investor)
Data Validation
Verified all companies are unique
Checked Valuation and Investor columns for consistency

Feature Encoding
Converted categorical variables (Continent, Country/Region, Investor) to numeric codes using label encoding
High Valuation Column
Categorized companies into High/Low Valuation based on the median valuation
