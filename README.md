# Netflix_Data_Analysis

This project performs exploratory data analysis (EDA) on a dataset of movies to uncover insights into trends, genres, popularity, and ratings. It uses Python libraries like **Pandas**, **Matplotlib**, **Seaborn**, and **NumPy** to clean, process, and visualize the data.

## 📁 Dataset

- **File Name**: `mymoviedb.csv`
- **Columns Include**:
  - Title
  - Genre
  - Release_Date
  - Vote_Count
  - Vote_Average
  - Popularity
  - Language

## 📌 Objectives

- Understand movie trends over the years.
- Analyze popularity and ratings across genres.
- Clean and preprocess date and numeric columns.
- Convert data types to improve analysis efficiency.
- Visualize vote counts, popularity, and trends.

## 🔧 Key Features

- **Datetime Conversion**: Extracts release year from release date.
- **Categorical Encoding**: Converts genre and language into category types.
- **Data Cleaning**: Handles invalid type casting and formatting issues.
- **Custom Functions**: Includes a function to categorize continuous variables using quantile edges.
- **Visualization**: Bar plots, line graphs, histograms, and scatter plots using Matplotlib and Seaborn.

## 🧪 Sample Analysis Performed

- Movies released per year
- Top genres by average rating
- Correlation between popularity and vote count
- Distribution of ratings and popularity
- Language-wise distribution of movies

## 📊 Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

## 🧹 Cleaning Techniques

- Removed malformed rows that couldn’t be parsed.
- Converted columns to appropriate data types (e.g., float, datetime, category).
- Used `pd.cut()` to group numerical columns into categorical bins.

## 📁 How to Run

1. Clone this repository or download the notebook.
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
