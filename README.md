# Investigating-Netflix-Movies
This project showcases an Exploratory Data Analysis (EDA) of Netflix movie data, focusing on 1990s trends. It highlights the most frequent movie durations, explores patterns in short action movies, and provides insights into the era's content. Skills demonstrated include data cleaning, filtering, and visualization using Python.

# Overview
This project focuses on performing exploratory data analysis (EDA) on Netflix movies from the 1990s. The goal is to uncover patterns and insights about movies from this nostalgic decade.

# The analysis answers the following questions:
What was the most frequent movie duration in the 1990s?
How many short action movies (less than 90 minutes) were released in this decade?
Dataset
The dataset used is netflix_data.csv, which contains information about Netflix shows and movies, including their release year, duration, genre, and more.

# Tools and Libraries
Python: Data manipulation and analysis.
Pandas: Reading and cleaning the dataset.
Matplotlib: Visualizing trends.

# Key Steps
# 1. Load the Dataset
I imported the dataset into VS Code, my preferred platform for open-source visualization and analysis. This allowed me to efficiently inspect and understand the structure of the dataset before proceeding with the analysis.

# 2. Inspecting the Dataset
I imported the necessary libraries, pandas and matplotlib, to work with the dataset and visualize the results. Here's why I used them:

Pandas: I imported pandas as pd because it’s a powerful library for data manipulation and analysis. It provides functions like read_csv() which allows me to easily load and handle large datasets, such as the Netflix dataset, in a structured format called a DataFrame.
Matplotlib: I imported matplotlib.pyplot as plt, which is a popular library for creating visualizations. The abbreviation plt is used as a convention for simplicity. While I didn’t create visualizations in this step, I imported it in preparation for any charts or plots I might need later to analyze the data.
After importing these libraries, I used pd.read_csv() to load the Netflix dataset into a DataFrame, as it is specifically designed to handle tabular data from CSV files. I chose the name netflix_df for the DataFrame to make it clear that it contains the Netflix dataset, and naming it this way helps keep the code readable and organized.

The dataset, now stored in netflix_df, contains 4,812 rows and 11 columns, including show_id, type, title, director, cast, country, date_added, release_year, duration, description, and genre. This step helped me understand the structure of the dataset and the details it contains, setting the stage for further analysis.

# 3. Data Cleaning
We can’t start work on data that isn’t clean because our findings will lead us to work that is not consistent and inaccurate. Let’s sort this first.

# Cleaning the Dataset
To ensure the data was ready for analysis, I needed to clean it by addressing any inconsistent, irrelevant, or missing data. Here's the process I considered:

# Inspect for Missing or Irregular Data:
I began by checking for missing or null values in the dataset. This step was essential for identifying gaps that might cause inconsistencies or skew analysis.
Check for Inconsistent Data:
I reviewed the dataset for columns with mixed or irrelevant data that didn’t align with the rest of the dataset. For instance, if any rows contained unexpected values or incorrect formats, I planned to clean or remove them.

# Handle Duplicates:
I examined the dataset for duplicate rows that could result from repeated data entries. Removing duplicates ensures each data point is unique, avoiding biased or inaccurate results.
Format Columns:
I ensured all columns were in the correct data type (e.g., numeric columns as integers or floats, text columns as strings). Any columns with incorrect data types were converted to the appropriate type.
Remove Irrelevant Columns:
If any columns were irrelevant to the analysis—such as unnecessary metadata or extra features—I would remove them to maintain focus on the most important data.
After this review, I found that my dataset required minimal cleaning. Issues such as duplicates or inconsistent data were not significant problems. Therefore, I decided to proceed directly with addressing the main analytical questions. I wrote code and used docstrings to explain my approach to each question in detail.

# 4. Filter for the 1990s
I filtered the dataset to include only movies released between 1990 and 1999, as this aligns with the scope and objectives of my project. This focus allowed me to delve deeper into the trends and characteristics of movies from this iconic decade.

# 5. Analyze Movie Durations
I identified the most frequent movie duration in the dataset to determine the preferred movie length during the 1990s. This analysis provided valuable insights and served as a great starting point to answer key questions about the dataset.

# 6. Count Short Action Movies
I determined the number of action movies with a runtime shorter than 90 minutes, as movies under 90 minutes were considered "short" during the 1990s. This insight prompted me to further analyze and identify how many movies were released in total during this iconic decade, providing a broader understanding of movie trends from the time.

# Findings
Most Frequent Movie Duration: The most frequent movie duration in the 1990s was approximately 94 minutes.
Short Action Movies: There were 7 short action movies released during the 1990s.

# Conclusion
The findings suggest that in the 1990s, movies generally favored a shorter runtime, with 94 minutes being the most common duration. This could indicate a trend towards more concise storytelling, driven by factors such as audience engagement, production constraints, or changing entertainment consumption patterns.

Additionally, the fact that there were 7 short action movies with a runtime under 90 minutes highlights a preference within the action genre for fast-paced films that get straight to the point. These insights provide valuable context for understanding the film industry of the 1990s and the preferences of both filmmakers and audiences during that time.

