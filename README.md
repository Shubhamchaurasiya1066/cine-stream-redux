# CineStream Redux

A modern movie streaming web application built using Next.js, Redux Toolkit, and TMDB API.

## Features

* Browse Popular Movies
* Movie Details Page
* Search Movies with Redux State Management
* Favorites Management using Redux Toolkit
* Dark / Light Theme Toggle
* Optimized Rendering with useMemo
* Responsive UI Design
* TMDB API Integration

## Tech Stack

* Next.js 16
* React 19
* Redux Toolkit
* React Redux
* Tailwind CSS
* TMDB API

## Installation

```bash
git clone https://github.com/your-username/cine-stream-redux.git
cd cine-stream-redux
npm install
npm run dev
```

## Environment Variables

Create a `.env.local` file and add:

```env
NEXT_PUBLIC_TMDB_API_KEY=4d9f8a64ab10f01805f4533fe8d498a8

## Redux Features

### Favorites Slice

* Add Movie to Favorites
* Store Favorite Movies Globally

### Filter Slice

* Global Search State
* Dynamic Movie Filtering

### Theme Slice

* Dark / Light Mode Toggle
* Global Theme Management

## Performance Optimization

* useMemo for optimized filtering
* Reduced unnecessary re-renders

## Author

Shubham Chaurasiya
