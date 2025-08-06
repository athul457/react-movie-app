# 🎬 Movie Explorer App

A modern React web application that lets users explore popular movies, search for specific titles, and manage a personalized favorites list — all powered by the TMDB API.

---

## 📸 Demo

[https://cinema-application-react.netlify.app/]

---

## 🚀 Features

- 🔍 **Search Movies**: Search for any movie using TMDB's API.
- 🌟 **Popular Movies**: Displays a list of trending/popular movies.
- ❤️ **Favorite Movies**: Add movies to your favorites list.
- 📌 **Context API**: Favorites list is globally managed using Context API.
- ⚛️ **React Hooks**: Built with `useState`, `useEffect`, and custom hooks.
- 💅 **Styled UI**: Clean and responsive user interface.

---

## 🧰 Tech Stack

- **Frontend**: React, JSX, CSS
- **API**: [The Movie Database (TMDB)](https://www.themoviedb.org/documentation/api)
- **State Management**: Context API
- **HTTP Requests**: Native `fetch`

---

## 🏗️ Project Structure

```
├── public/
├── src/
│ ├── components/
│ │ ├── MovieCard.jsx
│ │ └── FavoriteList.jsx
│ ├── context/
│ │ └── FavoriteContext.jsx
│ ├── services/
│ │ └── api.js
│ ├── pages/
│ │ └── Home.jsx
│ ├── App.jsx
│ ├── index.css
│ └── main.jsx
├── .env
├── package.json
└── README.md
```

```
git clone https://github.com/athul457/react-movie-app.git
cd react-movie-app
```
