# Movie Listing App

A React.js web application that allows users to search for movies, view detailed movie information, and browse movies with infinite scrolling. This project integrates the OMDB API and follows modern web development practices.

DEPLOYED LINK: https://movie-listing-app-09.netlify.app/

## Features

- Search movies using a debounced API call
- Type-ahead search suggestions
- Infinite scrolling for seamless browsing
- Movie details page with plot, genre, and other information
- Responsive design for mobile, tablet, and desktop
- Error handling for invalid searches and API failures
- Optimized UI with Bootstrap styling

## Tech Stack

- React.js (Functional Components & Hooks) 
- React Router (Navigation)
- Context API (State Management)
- Bootstrap (UI Components & Styling)
- OMDB API (Movie Database)
- Axios (API Calls)
- Lodash (Debounced Search)

## Installation and Setup

### Step 1: Clone the Repository
```sh
git clone https://github.com/Tushagangwar/movie-listing.git
cd movie-listing
```
### Step 2: Install Dependencies
```sh
npm install
```
### Step 3: Start the Development Server

## Usage Instructions

### Searching for a Movie
- Type a movie name in the search bar (e.g., "Avengers").
- The app will show real-time suggestions based on your input.
- Select a movie from the suggestions or press Enter to view the search results.

### Viewing Movie Details
- Click on any movie poster in the listing.
- You will be redirected to the Movie Details Page, which displays:
  - Title, Genre, and Year
  - Plot Summary
  - Movie Poster
  - Back Button to return to the previous page.

### Infinite Scrolling
- Scroll down the Movie Listing Page.
- The app will automatically load more movies when you reach the bottom of the page.

### Handling No Results
- If no movies match your search query, you will see a message:
