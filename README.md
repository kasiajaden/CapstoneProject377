# BeautyBot: Product Ratings Prediction
Kasia Windett | Applied Statistics & Probability | Spring / 2025

## Table of Contents
1. Project Overview
2. Data Description 
3. Project Structure
4. Project Flow
5. Notebook Sections
6. Results & Deliverables
7. Slide Deck
8. License


## Project Overview
### Problem Area

**Problem Statement**
More times than often, brands in the beauty industry have a hard time predicting whether or not their consumers will like a product they’re selling. Brands, retailers, product development and marketing teams often have trouble with predicting product success and customer satisfaction, identifying optimal pricing strategies, and understanding customer preferences.

**Proposed Solution**
A solution that is ideal for this type of problem is building a predictive model using data science. To be more specific, there will be multiple models built and developed to find the best one, such as linear regression. This ideal model will predict customer ratings, that way businesses can analyze their goals and customers more effectively. 

**Impact**
This solution will add value to businesses by having product improvement, inventory optimization, higher customer loyalty, and reduced return rates. Beauty companies will gain insight from the predictive feedback to tailor their formulas, packaging, or marketing strategy. Beauty retailers, such as Sephora, can predict which products will be rated high to stock more inventory or reduce their overstock on low-demand products. Customers will have fewer returns to make because the products will meet their expectations, if not, surpass them. 


## Dataset Description
- Source: Kaggle https://www.kaggle.com/datasets/raghadalharbi/all-products-available-on-sephora-website/data
- Raw Files: Located under 
- Processed files:


| File Name                | Description                                                   | 
|--------------------------|---------------------------------------------------------------|
| data/raw/                | Original data set                                             | 
| data/processed/train.csv | Cleaned & featured-engineered training set                    | 
| data/processed/test.csv  | Cleaned & featured-fengineered test set                       | 


## Project Structure
CapstoneProject/
├── README.md
├── .gitignore
│
├── data/
│ ├── raw/ # Immutable source data
│ └── processed/ # Cleaned, feature‑engineered data
│
├── notebook/ sephorawebsite.ipynb
│
├── slides/Captone_Final_Presentation.pdf
│
└── outputs/figures

## Project Flow
Raw Data Ingestion → Data Cleaning
Data Cleaning → Feature Engineering
Feature Engineering → Exploratory Data Analysis
EDA → Baseline Modeling
Baseline Modeling → Advanced Modeling & Optimization
Advanced Modeling → Model Evaluation & Interpretation
Evaluation → Deployment & Reporting

1. **Raw Data Ingestion** – load source files and validate schema.
2. **Data Cleaning** – handle missing values, remove duplicates, standardize formats.
3. **Feature Engineering** – create new variables, encode categoricals, scale numerics.
4. **Exploratory Data Analysis** – generate summary statistics and key visualizations.
5. **Baseline Modeling** – simple models to set performance benchmarks.
6. **Advanced Modeling & Optimization** – hyperparameter tuning, ensembles, or complex
architectures.
7. **Model Evaluation & Interpretation** – compare metrics.
8. **Deployment & Reporting** –  final model 

## Notebook Sections 
| Path                                                               | Purpose                                                       | 
|--------------------------------------------------------------------|---------------------------------------------------------------|
| notebook/sephorawebsite.ipynb#1-importing-libraries-and-dataset    | Data and library ingestion                                    | 
| notebook/sephorawebsite.ipynb#2-data-overview                      | Scoping the dataset                                           | 
| notebook/sephorawebsite.ipynb#3-preprocesssing-the-data            | Cleaning and saving processed data                            | 
| notebook/sephorawebsite.ipynb#4-exploratory-data-analysis          | Visual and statistical exploration of cleaned data            | 
| notebook/sephorawebsite.ipynb#5-baseline-models                    | Fit and evaluate initial benchmark models                     | 
| notebook/sephorawebsite.ipynb#6-advanced-modeling-and-optimization | Advanced modeling and optimization                            | 
| notebook/sephorawebsite.ipynb#7-model-comparisons-and-evalutions   | Model comparisons and final evaluation                        | 
| notebook/sephorawebsite.ipynb#8-conclusion                         | Conclusive thoughts and decisions                             | 

## Results & Deliverables
- **Final Model** – notebook/sephorawebsite.ipynb#6-advanced-modeling-and-optimization
- **Key Figures** – located in notebook/notebook/sephorawebsite.ipynb#7-model-comparisons-and-evalutions
- **Metrics Summary** – documented in notebooks and slide deck


## Slide Deck
Location: /slides/Capstone_Final_Presentation.pdf


## License
This project is licensed under the **CCNY License**.






