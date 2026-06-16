# AI Adoption Analytics (2023–2025)

## Project Overview

This project is an end-to-end data analytics and business intelligence project analyzing the evolution of AI adoption among developers worldwide between 2023 and 2025 using the Stack Overflow Developer Survey datasets.

The goal of the project is to understand:

* How AI adoption evolved over time
* How developers perceive and trust AI
* Which demographic groups adopt AI the most
* The impact of AI tools and AI agents on developer workflows
* Global trends in AI usage among software developers

The project combines:

* Python for data cleaning and exploratory analysis
* SQL-style analytics logic
* Power BI for interactive dashboarding and KPI visualization

---

# Objectives

* Analyze AI adoption trends from 2023 to 2025
* Measure sentiment and trust toward AI tools
* Compare adoption across age groups, countries, and developer profiles
* Study the rise of AI agents and advanced AI workflows in 2025
* Build interactive dashboards for storytelling and decision-making

---

# Technologies Used

* Python (Pandas, NumPy)
* SQL Analytics Logic
* Power BI
* Jupyter Notebook
* Stack Overflow Developer Survey Datasets

---

# Datasets

Source: Stack Overflow Annual Developer Survey

Datasets used:

* 2023 Survey Results
* 2024 Survey Results
* 2025 Survey Results

Official survey links:

* Stack Overflow Survey 2023
* Stack Overflow Survey 2024
* Stack Overflow Survey 2025

---

# Project Structure

---

│   AI Adoption Analytics Project Documentation.pdf
│
├───archive 2023
│   ├───Data_in
│   │       survey_results_public_2023.csv
│   │       survey_results_schema.csv
│   │
│   ├───Data_out
│   │       AI_Adoption_2023_Clean.csv
│   │       tech_ecosystem_dashboard.csv
│   │
│   ├───PowerBI
│   │       Dashboard_2023.pbix
│   │
│   └───Python
│           data_analysis_2023.ipynb
│           data_cleaning_2023.ipynb
│
├───archive 2024
│   ├───Data_in
│   │       survey_results_public_2024.csv
│   │
│   ├───Data_out
│   │       AI_Adoption_2024_Clean.csv
│   │       tech_ecosystem_dashboard.csv
│   │
│   ├───PowerBI
│   │       Dashboard_2024.pbix
│   │
│   └───Python
│           data_analysis_2024.ipynb
│           data_cleaning_2024.ipynb
│
├───archive 2025
│   ├───Data_in
│   │       survey_results_public_2025.csv
│   │       survey_results_schema.csv
│   │
│   ├───Data_out
│   │       AI_Adoption_2025_Clean.csv
│   │       ai_models_summary.csv
│   │
│   ├───PowerBI
│   │       Dashboard_2025.pbix
│   │
│   └───Python
│           data_analysis_2025.ipynb
│           data_cleaning_2025.ipynb
│
└───evolution 2023_2025
    ├───Data_out
    │       AI_Adoption_2023_2025.csv
    │
    ├───PowerBI
    │       evolution_dashboard.pbix
    │
    └───Python
            df_evolution.ipynb

---

# Data Cleaning

Main cleaning operations:

* Handling missing values
* Replacing null values with analytical categories:

  * No Response
  * Unknown
  * Unknown Country
* Harmonizing categories across years
* Creating grouped analytical features:

  * AI_Usage_Group
  * Sentiment_Group
  * Trust_Group
  * AI_Capability_Group
  * Agent_Adoption_Group
* Standardizing developer profiles

---

# Key Business Questions

## AI Adoption

* How did AI adoption evolve from 2023 to 2025?
* Which age groups use AI the most?
* Which countries lead AI adoption?

## AI Sentiment & Trust

* Are developers optimistic about AI?
* How much do developers trust AI tools?
* Does AI usage increase trust?

## AI Capabilities & Agents

* How capable are AI tools for complex tasks?
* How widely are AI agents adopted in 2025?
* What are the perceived benefits and limitations of AI?

---

# Dashboards

The Power BI report contains 4 dashboard pages:

## 1. AI Adoption Analytics 2023

Baseline AI adoption and perception insights.

## 2. AI Adoption Analytics 2024

Growth and maturity of AI adoption.

## 3. AI Adoption Analytics 2025

Advanced AI usage and AI agent adoption.

## 4. AI Adoption Evolution (2023–2025)

Cross-year comparison of adoption, trust, and sentiment trends.

---

# Main KPIs

* Total Respondents
* AI Adoption Rate
* Positive Sentiment Rate
* Trust Rate
* AI Agent Adoption Rate
* AI Capability Perception
* Country-Level Adoption
* Age Group Adoption Trends

---

# Key Insights

* AI adoption increased significantly between 2023 and 2025.
* Positive sentiment toward AI remained dominant across all years.
* Trust in AI grew more slowly than adoption.
* Younger developers showed higher AI adoption rates.
* AI agents became a major trend in 2025.

---

# Future Improvements

* Add salary and productivity impact analysis
* Build machine learning models for AI adoption prediction
* Add SQL database integration
* Deploy dashboards online

---

# Author

Fatima Ezzahra ElAAKARI

Aspiring Data Analyst | Power BI & SQL Enthusiast
