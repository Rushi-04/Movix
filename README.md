# Movix

Movix is a web application that allows users to search for movies, view trending movies, and see details about each movie. It utilizes the The Movie Database (TMDb) API for movie data and Appwrite for tracking trending searches.

## Live Project Link 
  https://movix-arena.vercel.app/  
  
  ( Used 'TMDb Movie API' so use vpn and then open website to load movies )

## Features

- **Search for movies:** Users can search for movies by title.
- **View trending movies:** The application displays a list of currently trending movies.
- **Movie details:** Users can view details for each movie, including the poster, title, rating, original language, and release year.
- **Responsive design:** The application is designed to be responsive and work on various screen sizes.

## Technologies Used

- **Frontend:**
  - React
  - Vite
  - Tailwind CSS
  - Flowbite React
  - React Icons
  - react-use
- **Backend:**
  - Appwrite (for tracking trending searches)
- **API:**
  - The Movie Database (TMDb) API

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- Node.js and npm installed on your machine.
- An API key from The Movie Database (TMDb).
- An Appwrite account with a project, database, and collection set up.

### Installation

1. **Clone the repo**
   ```sh
   git clone https://github.com/Rushi-04/React-Movie-App.git
   ```
2. **Install NPM packages**
   ```sh
   npm install
   ```
3. **Create a `.env` file** in the root of the project and add the following environment variables:
   ```
   VITE_TMDB_API_KEY=your_tmdb_api_key
   VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
   VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
   VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   ```
4. **Run the development server**
   ```sh
   npm run dev
   ```

## Usage

Once the development server is running, you can open your browser and navigate to `http://localhost:5173` to use the application. You can search for movies using the search bar, and the results will be displayed below. The trending movies section will show the most popular movies based on user searches.

## Project Structure

```
.
├── public
│   ├── hero-bg.png
│   ├── hero.png
│   ├── logo.png
│   ├── No-Poster.png
│   ├── search.svg
│   ├── star.svg
│   └── vite.svg
├── src
│   ├── assets
│   │   └── react.svg
│   ├── components
│   │   ├── AppFooter.jsx
│   │   ├── MovieCard.jsx
│   │   ├── Search.jsx
│   │   └── Spinner.jsx
│   ├── App.css
│   ├── App.jsx
│   ├── appwrite.js
│   ├── index.css
│   └── main.jsx
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── README.md
└── vite.config.js
```

