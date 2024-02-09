<h1 align="center">Olympics Data Analysis with SQL</h1>
<p align="center">
<img src="https://github.com/ayushmali1801/Olympics-Data-Analysis/assets/157601248/775c3d5f-9914-4e4e-b852-8dc2972b8f4d.type" width="500" height="300">
</p>
This project involves the analysis of an Olympics dataset using MySQL. The dataset includes information about athletes, their performances, and the medals won during various Olympic events. The primary goal is to extract meaningful insights and statistics from the dataset.

## Setup and Usage

1. Create a MySQL database named `project_1`.
<p>
<img src="https://github.com/ayushmali1801/Olympics-Data-Analysis/assets/157601248/38db4c21-17d6-444d-9f51-0b1ee3613267.type" width="180" height="130">
</p>


2. Create a table named `Olympics` to store the dataset.
   
<p>
<img src="https://github.com/ayushmali1801/Olympics-Data-Analysis/assets/157601248/214d011f-31ec-452a-930f-2787bbdb4fcf.type" width="200" height="300">
</p>


3. Load Data from CSV file

<p>
<img src="https://github.com/ayushmali1801/Olympics-Data-Analysis/assets/157601248/7bf203d2-94c1-4443-84cf-ccfa4d916b2b.type" width="650" height="300">
</p>


## Queries and Analysis

1. **Show how many medals counts present for entire data**
   - [SQL Query](queries/query1.sql)
   - [Result](results/result1.csv)

2. **Show count of unique sports present in Olympics**
   - [SQL Query](queries/query2.sql)
   - [Result](results/result2.csv)

3. **Show how many different medals won by team India**
   - [SQL Query](queries/query3.sql)
   - [Result](results/result3.csv)

...

## Insights Summary

- **Medal Distribution:** The dataset contains information on medals awarded in various Olympic events, indicating the overall competitiveness and achievement levels across different sports and countries.
- **Sport Diversity:** With a count of unique sports present in the dataset, it's evident that the Olympics encompass a wide range of sporting disciplines, showcasing the diversity and inclusivity of the event.
- **India's Performance:** Team India has participated in Olympic events and achieved success, as shown by the medals won. The breakdown of medals by event and year provides insights into India's strengths and areas of success in Olympic competition.
- **Global Performance:** The analysis of medal counts by country highlights the competitive landscape of the Olympics, showcasing countries with significant success in terms of medal acquisition.
- **Gold Medal Dominance:** The identification of countries with the most gold medals emphasizes the importance and prestige associated with winning gold in Olympic competition.
- **United States' Dominance:** The queries focusing on the United States reveal the country's remarkable success in the Olympics, both in terms of overall medal counts and gold medal achievements across different sports and years.
- **Top Performers:** Highlighting top-performing athletes and their achievements provides insights into individual excellence and contributions to their respective countries' success in the Olympics.
- **Gender Disparity:** The analysis of medals won by gender each year sheds light on gender-based trends and disparities in Olympic participation and success, offering insights into the representation and performance of male and female athletes over time.

## Setup and Usage

1. Set up MySQL database and create table using the provided schema.
2. Load data from CSV file into the database.
3. Execute SQL queries to perform analysis.

## Files Included

- `queries/`: Contains SQL queries for data analysis.
- `results/`: Contains CSV files with query results.

