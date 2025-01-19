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

## 📋 How to Use

### 1. Browse Popular Movies
- Navigate to the **homepage** to view a visually appealing grid of popular movies fetched dynamically from the TMDB API.

### 2. Search for Movies
- Use the **search bar** at the top of the page.
- Enter the **movie title** and press the **Search** button to display matching results instantly.

### 3. Add/Remove Favorites
- Click the **heart icon** on any movie card to:
  - **Add** the movie to your favorites list.
  - **Remove** the movie if it's already a favorite.
- Access all your favorites on the dedicated **Favorites page**.


## Screenshots
**Home page:**
![image](https://github.com/user-attachments/assets/1a464940-4ff8-44a7-aafb-b50a8471e6e0)
**Favorites page:**
![image](https://github.com/user-attachments/assets/4a65b4a2-3f8c-4765-867f-331652416163)

## 📚 API Reference

This app integrates with the **TMDB API** to fetch real-time movie data. Below are the key endpoints used:

### 1. **Get Popular Movies**
- **Endpoint:** `/movie/popular`
- **Description:** Fetches a list of currently popular movies.

### 2. **Search for Movies**
- **Endpoint:** `/search/movie`
- **Description:** Allows users to search for movies by their titles.

For more details, visit the [TMDB API Documentation](https://developers.themoviedb.org/3).



