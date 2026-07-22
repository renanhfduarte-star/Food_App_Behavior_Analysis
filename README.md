# 🛒 Food Startup App: User Behavior & A/A/B Testing

## 🎯 Project Overview
This repository contains a comprehensive data analysis project focused on user behavior and A/B testing for a food delivery startup. The goal is to investigate the sales funnel to understand user drop-off rates and evaluate the results of an A/A/B test regarding a proposed change in the app's UI fonts.

## 🛠️ Tools & Technologies
* **Python:** Core language for data processing.
* **Pandas:** Data manipulation, cleaning, and time-series filtering.
* **SciPy & Numpy:** Statistical hypothesis testing (Z-test for proportions).
* **Seaborn & Matplotlib:** Data visualization (Funnel charts and histograms).
* **Jupyter Notebook:** Interactive development and reporting.

## 📂 Repository Structure
* `app_behavior_analysis.ipynb`: The main Jupyter Notebook containing the code, statistical tests, and business conclusions.
* `datasets/`: Folder containing the initial server logs (`logs_exp_us.csv`).

## 💡 Key Business Insights
1. **Sales Funnel Performance:** The app has a remarkably high overall conversion rate, with **47.7%** of users completing a purchase after opening the app.
2. **Critical Drop-off Point:** The main bottleneck is the transition from the `MainScreen` to the `OffersScreen`, where the app loses **~38%** of its users. This is the primary area recommended for UX/UI optimization.
3. **A/A Test Validation:** The control groups (246 and 247) showed no statistically significant differences, validating the traffic-splitting mechanism.
4. **A/B Test Results (Font Change):** The statistical tests (Z-tests) revealed **no significant difference** between the control groups (old fonts) and the test group (new fonts) across any stage of the funnel. 
5. **Recommendation:** The new fonts do not harm conversion rates, but they also do not improve them. The company can safely deploy the new fonts if desired for branding purposes, but should not expect a boost in sales.