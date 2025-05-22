# 📺 Netflix Analysis SQL Project

## 📌 Project Overview
This project is a comprehensive **SQL analysis of Netflix data**, designed to extract key insights and solve business-related questions. Using SQL, we explore content trends, user preferences, country-wise distributions, and genre-based insights.

## 🗃 Dataset Schema

The dataset contains the following columns:

- `show_id`: Unique ID for each show
- `type`: Movie or TV Show
- `title`: Title of the content
- `director`: Director(s)
- `casts`: Main cast
- `country`: Country of production
- `date_added`: Date added to Netflix
- `release_year`: Year of release
- `rating`: Age rating
- `duration`: Duration in minutes/seasons
- `listed_in`: Genre(s)
- `description`: Content description

## ✅ Key Business Questions Solved

1. Count of Movies vs TV Shows
2. Most common rating for Movies and TV Shows
3. List of all movies released in a specific year (e.g., 2020)
4. Top 5 countries with the most Netflix content
5. Identify the longest movie
6. Content added in the last 5 years
7. All content by director ‘Rajiv Chilaka’
8. TV Shows with more than 5 seasons
9. Count of content in each genre
10. Average content released per year by India (top 5 years)
11. All documentaries
12. Content without a listed director
13. Count of movies with actor ‘Salman Khan’ in the last 10 years
14. Top 10 actors with the most appearances in Indian content
15. Categorize content as ‘Good’ or ‘Bad’ based on keywords ("kill", "violence")

## 🛠️ Technologies Used

- SQL (PostgreSQL syntax)
- PostgreSQL functions: `TO_DATE`, `EXTRACT`, `UNNEST`, `STRING_TO_ARRAY`, `CASE`, `RANK`, `PARTITION BY`, `WITH`

## 📂 File Structure

- `Netflix Analysis.sql`: SQL script file with all queries
- `README.md`: Project documentation

## 🔍 How to Use

1. Clone the repository
2. Import the dataset into a PostgreSQL database
3. Run the queries from `Netflix Analysis.sql` in your SQL client
4. Analyze results to derive insights

## 📈 Key Insights

- TV Shows slightly outnumber Movies in total content
- Most content is rated TV-MA and TV-14
- India is among the top countries producing Netflix content
- A significant amount of content lacks director information
- Certain actors frequently appear in Netflix’s Indian content
- Content descriptions can help classify themes (e.g., violence)


