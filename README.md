# movie-recommendation
# IMDb Movie Scraper

A simple Python script to fetch top movie titles from IMDb by genre.

This project scrapes IMDb search results for **feature films** in the selected genre and displays the top 10 titles. It uses **requests** and **BeautifulSoup** for web scraping.

---

## Features

- Fetches top movies from IMDb by genre:
  - Drama
  - Action
  - Comedy
  - Horror
  - Crime
- Displays up to 10 movie titles for readability.
- Simple and lightweight; no login or API keys required.

---

## Requirements

- Python 3.x
- Libraries:
  ```bash
  pip install requests beautifulsoup4 lxml

How to Run

Clone the repository:

git clone https://github.com/niharika-hande04/movie-recommendation.git


Activate your Python virtual environment (optional but recommended):

# Windows
.\emotion_env\Scripts\activate

# Linux/Mac
source emotion_env/bin/activate


Run the script:

python movie.py


Enter the genre when prompted:

Enter a genre (Drama, Action, Comedy, Horror, Crime):


Example input/output:

Enter a genre (Drama, Action, Comedy, Horror, Crime): Drama

Top movie titles:
The Shawshank Redemption
The Godfather
The Dark Knight
12 Angry Men
Schindler's List
Pulp Fiction
The Lord of the Rings: The Return of the King
Fight Club
Forrest Gump
Inception
