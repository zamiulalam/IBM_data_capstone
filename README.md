# Applied Data Science Capstone

This project marks the culmination of the IBM Data Science Professional Certificate specialization. As the 10th and final course, it brings together the skills and knowledge acquired throughout the program into a comprehensive, applied data science project.

## Project Background

SpaceX has emerged as the most successful player in the modern commercial space era, primarily due to its ability to reduce launch costs by reusing the first stage of its Falcon 9 rockets. While competitors charge upwards of $165 million per launch, SpaceX offers a significantly lower cost of $62 million. A key factor in this cost efficiency is the reusability of the rocket's first stage. This project aims to predict the likelihood of a first stage landing using publicly available data and machine learning models—ultimately helping to estimate launch costs.

## Research Questions

- How do factors such as payload mass, launch site, number of flights, and orbit type influence the success of first stage landings?
- Has the success rate of landings improved over time?
- Which binary classification algorithm performs best for this prediction task?

## Methodology

### 1. Data Collection
- Utilized SpaceX’s REST API.
- Employed web scraping techniques to extract complementary data from Wikipedia.

### 2. Data Wrangling
- Filtered and cleaned the dataset.
- Handled missing values appropriately.
- Applied One-Hot Encoding to prepare categorical variables for classification models.

### 3. Exploratory Data Analysis (EDA)
- Conducted EDA using visualizations and SQL queries to uncover patterns and relationships.

### 4. Interactive Visual Analytics
- Built interactive visualizations using Folium and Plotly Dash to explore the data dynamically.

### 5. Predictive Modeling
- Developed, tuned, and evaluated several classification models to predict landing outcomes and identify the most accurate approach.
