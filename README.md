# Food Startup App: User Behavior & A/A/B Testing

This repository contains a comprehensive data analysis project focused on user behavior and A/B testing for a food delivery startup. 

## Project Overview

The goal of this project is to investigate the sales funnel to understand user drop-off rates and evaluate the results of an A/A/B test regarding a proposed change in the app's UI fonts.

## Tools & Technologies

*   **Python:** Core language for data processing.
*   **Pandas:** Data manipulation, cleaning, and time-series filtering.
*   **SciPy & NumPy:** Statistical hypothesis testing (Z-test for proportions).
*   **Seaborn & Matplotlib:** Data visualization (Funnel charts and histograms).
*   **Jupyter Notebook:** Interactive development and reporting.

## Key Findings

| Insight Category | Key Finding |
| :--- | :--- |
| **Sales Funnel Performance** | The app has a remarkably high overall conversion rate, with 47.7% of users completing a purchase after opening the app. |
| **Critical Drop-off Point** | The main bottleneck is the transition from the MainScreen to the OffersScreen, where the app loses ~38% of its users. This is the primary area recommended for UX/UI optimization. |
| **A/A Test Validation** | The control groups (246 and 247) showed no statistically significant differences, validating the traffic-splitting mechanism. |
| **A/B Test Results (Font Change)** | The statistical tests (Z-tests) revealed no significant difference between the control groups (old fonts) and the test group (new fonts) across any stage of the funnel. |

## Strategic Recommendations

*   **Font Deployment Strategy:** The new fonts do not harm conversion rates, but they also do not improve them. The company can safely deploy the new fonts if desired for branding purposes, but should not expect a boost in sales. Optimization efforts and engineering resources should instead be redirected toward fixing the MainScreen to OffersScreen drop-off bottleneck.

## Repository Contents

*   `app_behavior_analysis.ipynb`: The main Jupyter Notebook containing the code, statistical tests, and business conclusions.
*   `datasets/`: Folder containing the initial server logs (`logs_exp_us.csv`).

---
This project was completed by Renan Henrique Duarte Ferreira as part of a Data Analytics curriculum.