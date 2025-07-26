# 🎬 IMDB Top 1000 Movies Analysis

This project is a beginner-friendly data analysis project using Python and Pandas. The goal is to explore and gain insights from the **Top 1000 Movies on IMDB** dataset.

---

## 📁 Dataset Information

- **Columns**:
  - `Series_Title` – Title of the movie
  - `Released_Year` – Year of release
  - `Certificate` – Age rating
  - `Runtime` – Duration of the movie
  - `Genre` – Main genres (comma-separated)
  - `IMDB_Rating` – User rating on IMDB
  - `Overview` – Short summary
  - `Meta_score` – Metacritic score
  - `Director` – Director's name
  - `Star1–Star4` – Main actors/actresses
  - `No_of_Votes` – Number of votes
  - `Gross` – Gross revenue (in USD)

---

## 🔍 Analysis Questions

Planned questions for EDA:

1. What are the **top-rated movies** by IMDB rating?
2. How does the **average rating vary by year**?
3. What are the **most common genres**?
4. Which directors have the **most movies** in the top 1000?
5. Is there any **correlation between runtime and rating**?
6. What are the **most-grossing movies**?

---

## 🧠 Summary of Insights

1. The top rated movies by IMDB rating
   - The Shawshank Redemption	(9.3)
   - The Godfather	(9.2)
   - 12 Angry Men	(9.0)
   - The Dark Knight	(9.0)
   - The Godfather: Part II	(9.0)
2. Average rating by 5 years
   - 1920-1924: 8.12
   - 1925-1929: 8.12
   - 1930-1934: 7.98
   - 1935-1939: 7.95
   - 1940-1944: 8.03
   - 1945-1949: 8.01
   - 1950-1954: 8.04
   - 1955-1959: 8.06
   - 1960-1964: 7.98
   - 1965-1969: 7.95
   - 1970-1974: 7.96
   - 1975-1979: 7.97
   - 1980-1984: 7.99
   - 1985-1989: 7.92
   - 1990-1994: 7.96
   - 1995-1999: 7.96
   - 2000-2004: 7.91
   - 2005-2009: 7.88
   - 2010-2014: 7.91
   - 2015-2019: 7.93
   - 2020: 8.13
3. The top 3 most common genres
   - Drama        724
   - Comedy       233
   - Crime        209
4. Top 3 directors
   - Alfred Hitchcock     14
   - Steven Spielberg     13
   - Hayao Miyazaki       11
5. Based on the correlation calculation, the Pearson correlation between Runtime and IMDB_Rating is 0.24, indicating a weak positive correlation.
   The scatterplot also shows that films with slightly longer runtimes tend to have higher ratings, but this relationship is not very strong.
6. Top 3 highest-grossing movies
   - Star Wars: Episode VII - The Force Awakens	$ 936662225
   - Avengers: Endgame	                        $ 858373000
   - Avatar	                                    $ 760507625

---

## 📊 Tools Used

- Python
- Pandas
- Matplotlib / Seaborn
- Google Colab

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Run all cells step-by-step
3. Explore the visualizations and outputs

---

## 🙋‍♂️ Author

- Faris SM | Beginner AI Enthusiast 🤖  
- Road to AI - Week 1 Project 🚀
