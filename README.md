# PlayStation 5 Games Dataset Analysis

## Overview
This project performs an analysis of PlayStation 5 games data, including information about game ratings, publishers, release dates, and age restrictions. The dataset is cleaned and processed to extract insights, with a focus on uncovering patterns in game ratings, publisher activity, and other key attributes.

## Table of Contents
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)

## Data Cleaning
The dataset contains information on PlayStation 5 games such as average ratings, total ratings count, publishers, and release dates. In this section, we:
1. Handle missing values by removing entries with missing publisher data.
2. Format the release date column.
3. Remove duplicate rows if present.

## Exploratory Data Analysis (EDA)
The EDA focuses on exploring the relationships within the data, including:
- Distribution of average ratings
- The number of games published by the top 10 publishers
- Correlation between average ratings and the total ratings count
- Age restriction analysis

## Visualizations
Various visualizations help in understanding the dataset:
1. **Distribution of Average Ratings**: A histogram with KDE shows the spread of ratings across games.
2. **Top Publishers by Number of Games**: A bar chart reveals which publishers are most active.
3. **Correlation Between Ratings and Total Ratings Count**: A scatter plot examines the relationship between game popularity and rating.
4. **Age Restriction Analysis**: A pie chart compares the proportion of age-restricted games to non-age-restricted games.

## Conclusion
The project provides insights into the PlayStation 5 gaming landscape by exploring key attributes like publisher performance and game ratings. These findings can assist in understanding trends in game releases and user preferences.

## Usage
To run the analysis, you will need the following Python libraries:
- pandas
- matplotlib
- seaborn

Install them using pip:
```bash
pip install pandas matplotlib seaborn

