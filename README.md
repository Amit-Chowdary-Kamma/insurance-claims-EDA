# Insurance Claims Exploratory Data Analysis

Exploratory data analysis on 6,249 auto insurance claims, uncovering patterns in customer demographics, pricing, and policy behavior to inform pricing and retention strategy.

## Overview

This project analyzes claims data from an automobile insurance company operating in the southwestern and western United States. The goal was to identify what drives differences between highly profitable customers and those who cost the company more than they generate in premium revenue, and to translate those patterns into actionable recommendations.

*Originally completed as a course project for a graduate business analytics program. The dataset was provided by the course; the analysis, code, visualizations, and write-up are my own.*

## Dataset

The dataset (`claims_df`) contains 6,249 individual auto insurance claims, with features covering:

- **Customer demographics** — state, education, employment status, gender, income, marital status
- **Policy details** — coverage tier, policy type, sales channel, months active
- **Vehicle information** — class, size
- **Claims history** — claim amounts, total claims, months since last claim
- **Business metrics** — monthly premium, customer lifetime value

## Key Questions Explored

The analysis answers 9 questions using summary statistics and visualizations (bar charts, histograms, pie charts, box plots, heatmaps, scatter plots, and violin plots), including:

- Which states have the largest customer bases
- How income is distributed across the customer population
- What vehicle classes customers most commonly own
- Whether monthly premiums differ significantly by gender
- How coverage type relates to marital status
- Correlations between income, claims, and other numeric variables
- The relationship between income and monthly premium
- How sales channel impacts premium values
- How residence type and vehicle class intersect

## Key Findings

- California and Oregon represent the company's largest markets, while states like Nevada and Washington are underrepresented, suggesting a potential growth opportunity
- Most customers fall into a middle-income range ($20,000–$75,000), indicating a fairly income-homogeneous customer base
- Four-door and two-door cars dominate the vehicle mix (roughly 70% combined), pointing to a cost-conscious customer segment
- Premium differences by gender are modest but present, with female customers showing a wider spread of high-premium outliers

## Tools Used

- **Language:** R
- **Libraries:** tidyverse, ggplot2, dplyr
- **Environment:** Jupyter Notebook

## Project Structure
