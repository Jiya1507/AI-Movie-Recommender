# 🎬 AI Movie & Series Recommender

<div align="center">

### 🍿 Discover something worth watching.

A modern, dark-themed movie & TV discovery web app powered by **The Movie Database (TMDB) API**, with genre-based recommendations, trending content, streaming picks, Indian cinema discovery, ratings, trailers, and detailed movie/series information.

<br/>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111111)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![TMDB](https://img.shields.io/badge/TMDB_API-01B4E4?style=for-the-badge&logo=themoviedatabase&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-7C3AED?style=for-the-badge)

</div>

---

## ✨ About The Project

**AI Movie & Series Recommender** is an interactive movie and TV discovery website designed to help users quickly find something interesting to watch.

The application uses the **TMDB API** to search, discover, filter, sort, and display movies and TV shows.

Users can:

- 🔎 Search for movies or TV series
- 🎯 Filter recommendations by genre
- 🔥 Explore weekly trending content
- ⭐ Sort results by rating
- 📈 Sort results by popularity
- 🆕 Sort results by newest releases
- 🎬 View detailed movie and series information
- ▶️ Watch available trailers
- 📺 Explore Netflix and Amazon Prime content
- 🇮🇳 Discover popular Indian movies
- ⭐ View ratings and release information
- 🎞️ Explore posters and movie details through an interactive UI

> **Note:** Despite the project name, the current implementation is a TMDB API-driven recommendation/discovery system rather than a machine-learning recommendation model.

---

# 🎥 Features

## 🔎 Movie & Series Search

Search for any movie or TV series using the search bar.

The application uses TMDB's multi-search API and displays both:

- 🎬 Movies
- 📺 TV Shows

---

## 🎯 Genre-Based Recommendations

Users can select one or multiple genres.

### Available Genres

| Genre | TMDB ID |
|---|---:|
| 💥 Action | `28` |
| 😂 Comedy | `35` |
| 🎭 Drama | `18` |
| 🚀 Sci-Fi | `878` |
| 👻 Horror | `27` |
| ❤️ Romance | `10749` |
| 🎥 Documentary | `99` |

After selecting genres, the application fetches matching movies and TV shows and combines them into a single recommendation feed.

---

## 🔥 Trending Recommendations

If no genre is selected, the application automatically loads **weekly trending movies and TV shows** from TMDB.

```text
No Genre Selected
       ↓
Get Recommendations
       ↓
TMDB Weekly Trending
       ↓
Movies + TV Shows
       ↓
Sort Results
       ↓
Display Recommendations
