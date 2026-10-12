# Anecdote Roulette

An interactive **React web application** designed to showcase software engineering quotes and track real-time voting analytics.

## Features
* **Anecdote Roulette:** Instantly display a randomized software engineering quote at the click of a button.
* **Immutable Voting Engine:** Safely log votes for the active quote without violating React state constraints.
* **Real-time Leaderboard:** Automatically isolates and highlights the single most popular anecdote on the fly.

## Tracked Metrics
* **Vote Count:** Individual cumulative scores maintained for each distinct anecdote entry.
* **Popularity Index:** Dynamic calculation to determine which index commands the highest user engagement.
* **Conditional Logic:** Safely triggers a fallback layout to prevent winner declarations until the very first vote is cast.

## Tech Stack
* **Frontend Library:** [React](https://react.dev)
* **State Management:** Functional components utilizing React `useState` hooks.
* **Build System:** Designed for compatibility with [Vite](https://vite.dev) or Create React App.

---
*Developed as part of functional components and state handling practices.*
