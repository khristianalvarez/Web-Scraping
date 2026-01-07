# Web-Scraping

#### *This folder showcases previous web scraping projects I have completed, primarily using Beautiful Soup. Further details for each exercise are outlined below:*

## Scraping Coronavirus Data

### Scraping_Converting_Cleaning_COVID_data.ipynb

This project uses web scraping techniques to collect up-to-date global COVID-19 statistics from the Worldometers coronavirus page. The dataset includes metrics such as total cases, total deaths, new cases, new deaths, active cases, serious and critical cases, total recovered cases, and newly recovered cases.


## Scraping Movie Information from the British Board of Film Classification (BBFC) Website

### Web_Scraping_Exercise_Movie_Info_British_Film_Board.ipynb

In this exercise, I developed advanced, user-defined helper functions to extract detailed movie information from the BBFC website.

#### Scraping the “Recent Releases” page:

- Data was extracted by identifying relevant h4 tags and their sibling elements, or by locating specific div elements and retrieving their text content.
- 
- Extracted fields include: Title, Rating Content, Synopsis, Classified Date, Language, Director(s), Production Year, Release Date, Genre, Running Time, and Cast.

  
#### Scraping data from a predefined list of movie titles:

- A helper function was built to iterate through a list of movie titles, retrieve each corresponding URL, and scrape detailed information using a dedicated scrape_movie_info function.
  
- Extracted fields include: Title, URL, Type, Rating, Content, Synopsis, Classified Date, Language, Director, Production Year, Genre, Running Time, Cast, and UK Age Rating.


## Scraping Largest Companies by Revenue

### Web_scraping_with_beautiful_soup_Fin4Tomorrow_case_study.ipynb

This exercise involves scraping Wikipedia’s List of largest companies by revenue (2021) to collect information on the world’s largest companies by revenue.


