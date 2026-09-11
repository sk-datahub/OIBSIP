# OIBSIP — Data Analytics Final Submission

This package contains the four Level-1 Data Analytics tasks completed against the OASIS INFOBYTE SIP checklist. The supplied task list requires at least 3 Data Analytics tasks; completing all four Level-1 tasks exceeds that minimum.

## Tasks
1. EDA on Retail Sales Data
2. Customer Segmentation Analysis
3. Cleaning Data
4. Sentiment Analysis

## Structure
- Each task has a Jupyter Notebook (`.ipynb`).
- `data/` contains the datasets used.
- `outputs/` contains generated CSV outputs after notebook execution.

## Run
Install: `pip install pandas numpy matplotlib seaborn scikit-learn wordcloud jupyter nbformat nbconvert`
Then open the notebooks in Jupyter and Run All.

## Important source note
Task 1 uses the uploaded 2024 Indian FMCG dataset. Because it has no literal product-name field, the notebook explicitly uses `Brand + Category` as a Product Proxy rather than silently inventing product names.

Task 2 and Task 4 use reproducible practice datasets generated specifically to satisfy the behavioural-segmentation and text-classification workflow.
