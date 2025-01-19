# 🎬 Movie App

A React-based web application that allows users to browse popular movies, search for specific titles, and mark their favorite movies. This project uses The Movie Database (TMDB) API to fetch movie data dynamically.

---

## 🚀 Features
- **Browse Popular Movies:** Displays a grid of popular movies fetched from TMDB.
- **Search Functionality:** Search for movies by their title using the TMDB search endpoint.
- **Favorites:** Add movies to your favorites list by clicking on the heart button.
- **Responsive Design:** Optimized for both desktop and mobile devices.

---

## 🛠️ Technologies Used
- **Frontend:** React.js (Hooks, Context API)
- **Styling:** CSS
- **API:** TMDB API

---

## 🛠️ Setup Instructions

### Prerequisites
- **Node.js** and **npm/yarn** installed on your machine.

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/movie-app.git
   cd movie-app

2. **Install dependencies:**
   ```bash
   npm install

3. **Set up environment variables:**
   Create a credential.js file in the root directory and add the following code:
   ```javascript
   export const API_KEY = 'your_tmdb_api_key';
   export const BASE_URL = 'https://api.themoviedb.org/3';
   
4. **Start the development server:**
   ```bash
   npm run dev

5. **Open your browser and navigate to:**
   ```arduino
   http://localhost:3000
