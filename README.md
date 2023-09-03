# NETFLIX-EDA

# Netflix Exploratory Data Analysis (EDA)

## Overview

This project involves an exploratory data analysis (EDA) of a Netflix dataset. The dataset contains information about Netflix shows and movies, including details such as show ID, category, title, director, cast, country, release date, rating, duration, type, and description. The EDA aims to uncover insights and patterns within the data, providing valuable information about the content available on Netflix.

## Dataset

- **Dataset Source:** contains outside netflix.csv
- **Format:** CSV
- **Columns:**
  - **Show_Id**: Unique identifier for the show or movie
  - **Category**: Whether it's a TV Show or Movie
  - **Title**: Title of the show or movie
  - **Director**: Director's name (if available)
  - **Cast**: Cast members
  - **Country**: Country of origin
  - **Release_Date**: Release date
  - **Rating**: Content rating
  - **Duration**: Duration of the show or movie
  - **Type**: Genre or type of content
  - **Description**: Brief description of the show or movie

## Analysis

### Getting Basic Information about the Dataset

```python
# Importing necessary libraries
import pandas as pd
import seaborn as sns



## Questions

1. **Is there any duplicate record in this dataset? If yes, remove the duplicate records.**
   - Code: See Task 1 in the code snippets.
   
2. **Are there any null values present in any column? Show with a heatmap.**
   - Code: See Task 2 in the code snippets.
   
3. **For "House of Cards," what is the show ID, and who is the director of this show?**
   - Code: See Q1 in the code snippets.

4. **In which year were the highest number of TV shows and movies released? Show with a bar graph.**
   - Code: See Q2 in the code snippets.

5. **How many movies and TV shows are in the dataset? Show with a bar graph.**
   - Code: See Q3 in the code snippets.

6. **Show all the movies that were released in the year 2000.**
   - Code: See Q4 in the code snippets.

7. **Show only the title of all TV shows that were released in India only.**
   - Code: See Q5 in the code snippets.

8. **Show the top 10 directors who gave the highest number of TV shows and movies to Netflix.**
   - Code: See Q6 in the code snippets.

9. **Show all the records where the category is "Movie" and "Type is Comedies" OR "Country is United Kingdom."**
   - Code: See Q7 in the code snippets.

10. **In how many movies/shows was Tom Cruise cast?**
    - Code: See Q8 in the code snippets.

11. **What are the different ratings defined by Netflix?**
    - Code: See Q9 in the code snippets.

12. **How many movies got the "TV-14" rating in Canada?**
    - Code: See Q9i in the code snippets.

13. **How many TV shows got the "R" rating after the year 2018?**
    - Code: See Q9ii in the code snippets.

For detailed explanations and code snippets for each question, please refer to the respective sections in the code snippets provided in this repository.

