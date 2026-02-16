# 🎬 MovieHunt – Find Your Next Watch

MovieHunt is a modern, responsive web application that lets you discover trending movies, search through millions of titles, and get detailed information – all powered by **The Movie Database (TMDB) API**. Save your favourites locally and explore where to watch them on popular streaming platforms.

## Home Page
![Home Page](/movie%20hunter/screenshots/Home%20page.png) 
---
## Favorites Tab 
![Favorites Tab](/movie%20hunter/screenshots/favs%20tab.png)  
---
## Search state
![Search state](/movie%20hunter/screenshots/search%20state.jpg)  
---
## Loading state
![Loading state](/movie%20hunter/screenshots/Loading%20state.png)
---
## Empty state
![Empty state](/movie%20hunter/screenshots/Empty%20state.png)
---

## ✨ Features

- **Trending Movies** – See the most popular movies of the day right on the home page.
- **Search** – Find any movie by title with a fast, responsive search.
- **Movie Details** – Click any card to open a beautiful modal with:
  - Poster, title, tagline, rating, runtime, release year
  - Genre badges
  - Overview
  - Direct links to YouTube trailer, Netflix, and Amazon Prime searches
- **Favourites** – ❤️ Add/remove movies to your personal favourites list (stored in your browser's `localStorage`).
- **Fully Responsive** – Works flawlessly on mobile, tablet, and desktop.
- **Loading Spinner** – Smooth 3D animated spinner while data loads.
- **Error Handling** – Friendly error messages if something goes wrong.

---

## 🛠️ Technologies Used

- **HTML5** – Semantic markup
- **CSS3** – Custom properties (variables), Flexbox, Grid, animations
- **JavaScript (ES6+)** – Modular architecture, async/await, DOM manipulation
- **[TMDB API](https://www.themoviedb.org/documentation/api)** – Movie data and images
- **[Font Awesome](https://fontawesome.com/)** – Icons
- **LocalStorage** – Persist favourite movies

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, etc.)
- (Optional) A text editor if you want to modify the code

### Installation

1. **Clone the repository**
  - git clone [https://github.com/SharjeelArshad0220/moviehunt.git](https://github.com/SharjeelArshad0220/Movie-Hunter/)
  - cd moviehunt

2. **Open the app**
   - Simply open `index.html` in your browser.

3. **Get your own API key (optional but recommended)**
   - The project currently uses a hardcoded demo key (`8ccdd5462b8312deb7c49289201f7656`). For production or personal use, please get your own free key from [TMDB](https://www.themoviedb.org/settings/api).
   - Replace the `API_KEY` variable in `utility.js` with your new key.

> ⚠️ **Note**: Because this is a client-side app, the API key is exposed in the source code. In a real‑world scenario you would proxy requests through a backend to hide the key. This project is intended for learning/portfolio purposes.

---

## 📖 Usage

- **Home** – Displays trending movies (default view). Click the **Home** button in the navbar to return.
- **Search** – Type at least two characters in the search box and press Enter or click the **Search** button.
- **Favourites** – Click the heart icon on any movie card to add/remove it from your favourites. Click **My Favorites ❤️** in the navbar to see your saved movies.
- **Movie Details** – Click anywhere on a movie card (except the heart) to open the details modal.
- **Modal** – View full details and click the streaming links to search for the movie on YouTube, Netflix, or Amazon Prime.

---

## 📁 Project Structure

```
moviehunt/
│
├── index.html          # Main HTML file
├── style.css           # All styles (responsive, themes, loader)
├── app.js              # Entry point – event listeners and initial load
├── utility.js          # All core functions (API calls, rendering, favourites)
├── no-image.png        # Fallback image when poster is missing
└── README.md           # You are here
```

---

## 🔮 Future Enhancements

- Pagination for search results and trending lists
- User authentication to sync favourites across devices
- More streaming provider links (Disney+, Apple TV, etc.)
- Dark/light theme toggle
- Filter by genre or year
- Accessibility improvements

---

## 🙏 Acknowledgements

- [The Movie Database (TMDB)](https://www.themoviedb.org/) for providing the amazing API and movie data.
- [Font Awesome](https://fontawesome.com/) for the icons.
- Inspiration from Netflix, Prime Video, and modern streaming interfaces.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Made with ❤️ by Sharjeel Arshad**  
*Happy movie hunting!* 🍿
```