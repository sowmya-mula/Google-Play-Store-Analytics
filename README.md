# Google Play Store Analytics

## Internship Project – Google Play Store Data Analytics and Visualization

This project was completed as part of my internship training in data analytics. The project focuses on analyzing Google Play Store application data using Python, Pandas, Plotly, and data visualization techniques.

## Project Overview

The objective of this project is to analyze Google Play Store applications and extract meaningful insights from application ratings, reviews, installs, size, categories, content ratings, pricing, and revenue-related information.

The project contains six analytical tasks covering data cleaning, exploratory analysis, geographic visualization, time-series analysis, category comparison, and free-versus-paid application analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Plotly
- Jupyter Notebook
- Data Cleaning
- Data Analysis
- Data Visualization
- Statistical Analysis

## Datasets

The project uses Google Play Store application data and user review data.

Main datasets include:

- Google Play Store application dataset
- Google Play Store user reviews dataset
- Merged Google Play Store dataset

## Project Tasks

### Task 1 – Bubble Chart Analysis

Analyzed application size and rating using a bubble chart.

The analysis considered:

- Application size
- Rating
- Number of installs
- Category
- Reviews
- Sentiment subjectivity

The bubble size represents the number of installs.

---

### Task 2 – Global Install Analysis

Analyzed total installs across selected application categories and created a geographical visualization.

Top categories identified include:

- Productivity
- Tools
- Family
- Photography
- News & Magazines

---

### Task 3 – Category Time-Series Analysis

Performed monthly analysis of application installs for selected categories.

The analysis identified periods where category installs showed significant month-over-month growth.

---

### Task 4 – Stacked Area Analysis

Created a stacked area chart to analyze monthly install trends for selected application categories.

The analysis considered:

- Rating
- Reviews
- Application size
- Category
- Monthly installs
- Growth percentage

---

### Task 5 – Category Comparison

Created a grouped bar chart comparing the top application categories based on installs.

The analysis applied filters based on:

- Application rating
- Application size
- Last updated month
- Category
- Number of installs

---

### Task 6 – Free vs Paid Application Analysis

Analyzed free and paid applications across the top application categories.

The analysis considered:

- Application type
- Category
- Installs
- Price
- Revenue
- Android version
- Content rating
- Application name length

A revenue-based filter was applied to identify qualifying paid applications.

## Project Structure

```text
Google-Play-Store-Analytics/
│
├── datasets/
│
├── task1/
├── task2/
├── task3/
├── task4/
├── task5/
├── task6/
│
├── assets/
│
├── index.html
├── README.md
└── LICENSE
