# usePopcorn

A recruiter-friendly React movie search and watchlist app. It lets users search OMDb, inspect movie details, rate titles, and persist a personal watchlist in the browser.

## Recruiter Quick View

- **What to look for:** API loading states, error handling, custom hooks, localStorage persistence, keyboard shortcuts, and component composition.
- **Production:** Built for Vercel from the `master` branch.
- **Important config:** Vercel needs `REACT_APP_OMDB_API_KEY` for live search.

## Features

- Search movies by title through the OMDb API.
- Inspect runtime, genre, release date, cast, director, plot, and IMDb rating.
- Rate movies with a reusable star rating component.
- Save and remove watched movies with browser persistence.
- Watchlist analytics for saved titles, average ratings, and runtime.
- Responsive layout with clear empty, loading, and error states.

## Tech Stack

- React 19
- Create React App
- Custom React hooks
- OMDb API
- localStorage
- CSS responsive layout

## Run Locally

```bash
npm install
```

Create a `.env` file:

```bash
REACT_APP_OMDB_API_KEY=your_omdb_key_here
```

Start the app:

```bash
npm start
```

Build for production:

```bash
npm run build
```

## Notes

This project is intentionally small, but it demonstrates production-facing habits: graceful missing-config handling, readable state flow, reusable hooks, resilient empty states, and recruiter-readable documentation.
