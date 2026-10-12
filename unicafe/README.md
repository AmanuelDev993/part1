# Feedback App (Unicafe)

A lightweight, interactive **React web application** designed to collect customer feedback and display real-time statistics. 

## Features
* **Feedback Collection:** Simple buttons to log **Good**, **Neutral**, or **Bad** experiences.
* **Real-time Statistics:** Automatically calculates aggregate data inside a clean tabular layout.
* **Conditional Rendering:** Softly prompts users with a fallback message until the first piece of feedback is provided.

## Tracked Metrics
* **Total:** Accumulative count of all feedback received.
* **Average Score:** Weighted average where Good = 1, Neutral = 0, and Bad = -1.
* **Positive Percentage:** Percentage share of "Good" ratings relative to the total.

## Tech Stack
* **Frontend Library:** [React](https://react.dev)
* **State Management:** Functional components utilizing React `useState` hooks.
* **Build System:** Designed for compatibility with [Vite](https://vite.dev) or Create React App.

---
*Developed as part of functional components and state handling practices.*
