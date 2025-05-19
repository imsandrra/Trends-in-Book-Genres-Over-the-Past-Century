# Trends in Book Genres Over the Past Century

## Project Overview
This project analyzes trends in book genres over the past century using the "Best Books Ever" dataset from Kaggle. The dataset is available at [this link](https://www.kaggle.com/datasets/pooriamst/best-books-ever-dataset). The goal is to explore the distribution and popularity of book genres from 1916 to 2017 through data visualization and statistical analysis.

## Important Note on Dataset
The dataset provides publication dates in the format **mm/dd/yy** (e.g., 04/25/11). However, it is unclear whether **11** refers to the year 2011, 1911, or even 1811. Due to this ambiguity, it is recommended to approach this project from a **technical perspective** rather than focusing on historical insights.

## Features
- **Data Cleaning & Preparation**: Filtering and structuring book genre data.
- **Time Series Analysis**: Identifying trends in genre popularity over time.
- **Top Genres Per Year**: Extracting the most popular book genres annually.
- **Data Visualization**: Interactive and static plots to illustrate trends and distributions.

## Technologies Used
- **R Programming Language**
- **Libraries**:
  - `ggplot2` for static data visualization
  - `plotly` for interactive plots
  - `dplyr` and `tidyverse` for data manipulation
  - `lubridate` for date handling

## Data Processing Steps
1. **Filtering & Cleaning**: Extract relevant columns and clean missing/invalid entries.
2. **Date Transformation**: Convert `firstPublishDate` to a standard format while addressing ambiguities.
3. **Genre Selection**: Focus on the top 5 most popular genres per year.
4. **Visualization**:
   - **Stacked Area Plot**: Illustrates genre trends over time.
   - **Pie Chart**: Displays the distribution of book genres.

## Key Insights
- **Rising Popularity**: Genres such as Young Adult, Fantasy, and Romance have grown in prominence.
- **Declining Genres**: Historical Fiction and Novels have seen a decline.
- **Dominant Genres**: Fiction and Fantasy lead book publications in terms of share.
- **Overall Growth**: A steady increase in book publications highlights an expanding literary landscape.

## How to Use This Project
1. Clone this repository.
2. Install necessary R libraries:
   ```r
   install.packages("plotly")
   install.packages("dplyr")
   install.packages("tidyverse")
   install.packages("ggplot2")
   install.packages("lubridate")
   ```
3. Load the dataset and run the scripts for analysis and visualization.

### Result Project
You are welcomed to see the final result project using this link[https://rpubs.com/imsandrra/1284402]

## Conclusion
This project provides valuable insights into book genre trends over time. However, due to the uncertainty in date formatting, the focus should remain on technical execution rather than drawing historical conclusions.

