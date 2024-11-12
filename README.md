# YouTube-Channel-Insights

## Project Overview
This project is dedicated to enhancing the Australian Taxation Office’s (ATO) and similar government-related YouTube channels' engagement and overall effectiveness through data-driven insights. By analyzing video content trends, audience engagement metrics, and key performance indicators, this work aims to guide content strategy improvements and optimize audience interaction. The analysis begins with foundational data extraction and exploratory data analysis (EDA), progressing into predictive modeling and advanced analytics, including machine learning (ML) and deep learning (DL), to provide actionable insights for content strategy refinement.

## Project Structure

- **notebooks/**: 
  - [Data Extraction Notebook](https://github.com/EsmaeilNarimissa/YouTube-DataDriven-Upgrade/blob/main/DataExtrac_Youtube_4.ipynb): Contains code for extracting relevant video data using the YouTube API.
  - [Exploratory Data Analysis (EDA) Notebook - Chapters 1 & 2](https://github.com/EsmaeilNarimissa/YouTube-DataDriven-Upgrade/blob/main/MAIN_EDA.ipynb): Covers data exploration, visualization, and initial insights into engagement trends and content characteristics across domains.
  - [Machine Learning and Deep Learning Notebook](https://github.com/EsmaeilNarimissa/YouTube-DataDriven-Upgrade/blob/main/ML_YouTube.ipynb): Implements ML and DL models to identify factors impacting video engagement and provides feature importance insights using SHAP analysis.
- **data/**: Contains raw and processed CSV files with extracted video data for analysis.
- **src/**: Source code for data processing, feature engineering, and analytical functions.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/EsmaeilNarimissa/YouTube-DataDriven-Upgrade.git
   ```
2. **Install dependencies** (consider using a virtual environment):
   ```bash
   pip install -r requirements.txt
   ```
3. **Run notebooks**:
- Start with [DataExtrac_Youtube_4.ipynb](https://github.com/EsmaeilNarimissa/YouTube-DataDriven-Upgrade/blob/main/DataExtrac_Youtube_4.ipynb) to replicate data collection.
- Proceed to [MAIN_EDA.ipynb](https://github.com/EsmaeilNarimissa/YouTube-DataDriven-Upgrade/blob/main/MAIN_EDA.ipynb) to explore initial analyses and insights.
- Finally, use [ML_YouTube.ipynb](https://github.com/EsmaeilNarimissa/YouTube-DataDriven-Upgrade/blob/main/ML_YouTube.ipynb) for machine learning models and feature importance insights, guiding strategic recommendations.


## Data Sources
Data is retrieved directly from the YouTube API, focusing on government-related channels, including tax, health, and service departments from multiple countries. This data forms the basis for insights on video content performance, engagement metrics, and publishing strategies.

