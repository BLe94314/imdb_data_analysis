## 1. Introduction
This data project scrapes IMBb's Top 250 movies, processes the data, and uncovers insights on various movies through data analysis and visualizations.
## 2. Objective
<ol>
  <li>Showcases web scraping skills.</li>
  <li>Demonstrates data cleaning and preprocessing.</li>
  <li>Conducts data analysis and visualizes information.</li>
  <li>Discovers insights with practical applications for users and companies.</li>
</ol>

## 3. Dataset
<ol>
  <li>Data scraped from <a href="https://www.imdb.com/chart/top/">IMDb's Top 250 Movies.</a></li>
  <li>Contains the following columns:</li>
  <ol>
    <li>Title</li>
    <li>Release Year</li>
    <li>Genres</li>
    <li>Runtime</li>
    <li>Rating</li>
    <li>Age Rating</li>
  </ol>
</ol>

## 4. Technologies
<ol>
  <li>Python (requests, BeautifulSoup, pandas, matplotlib)</li>
  <li>Google Colab</li>
</ol>

## 5. Results
<ol>
  <li>The most common genre throughout the decades has been drama.</li>
  <li>Most of the top movies were released in the 1990s.</li>
  <li>R-rated movies have the highest occurrence, but PG-13 movies have a slightly higher average rating.</li>
</ol>
<img width="678" height="470" alt="distribution_of_imdb_ratings" src="https://github.com/user-attachments/assets/7ac04e1a-c853-43c7-b20a-b152be09442e" />
<img width="686" height="491" alt="distribution_of_age_ratings_by_decade" src="https://github.com/user-attachments/assets/7d92e386-6aee-4cdb-90d9-c74462e74d37" />
<img width="686" height="470" alt="distribution_of_movies_per_decade" src="https://github.com/user-attachments/assets/1d4ea2de-15b4-441b-b5f0-1ba82dcb52f6" />

## 6. GitHub Structure
<ol>
  <li>notebooks/: main analysis notebook</li>
  <li>data/: uncleaned and cleaned datasets</li>
  <li>visuals/: saved visualizations</li>
</ol>

## 7. How to Run
Download the .ipynb file and run it into Google Colab or Jupyter Notebooks.

## 8. Future Improvements
<ol>
  <li>Scrape box office data to analyze and predict profitability.</li>
  <li>Include directors, main actors, and producers to assess their impact on profit and critical acclaim.</li>
  <li>Scrape results from other review sites (e.g., Metacritic and Rotten Tomatoes).</li>
</ol>
