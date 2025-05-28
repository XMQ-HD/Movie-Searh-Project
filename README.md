# 🎬 Movie Finder

A super-lightweight movie-search front end.  
- **Key features**  
  - **Trending list** – shows the most-popular titles from TMDB by default.  
  - **Keyword search** – type a word and instantly get movie details (title, poster, rating, … ).  
  - **Search-count tracking** – every query is stored in an Appwrite database and its counter is incremented, so the app can display a “Trending Searches” chart.  

- **Better search UX**  
  - **Custom 300 ms debounce** – the app waits until the user stops typing for 300 ms before calling the TMDB API, cutting unnecessary requests and flicker.  
  - Poster fallback – if a movie has no poster or 404s, an in-app placeholder image is shown instead.  

> Live demo 👉 <https://movie.xmqzone.com>
