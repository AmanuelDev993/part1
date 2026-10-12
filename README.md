# Full Stack Open - Part 1

This repository contains my completed exercises for **Part 1** of University of Helsinki's **Full Stack Open** curriculum. The course covers deep core concepts of modern web development using **React**, focusing on components, state management, event handling, and functional JavaScript.

## 📂 Repository Structure

The exercises are split into three independent React applications:

*   **`courseinfo/`** (Exercises 1.1 - 1.5)
    *   An introductory application rendering course metadata, content fragments, and exercises.
    *   *Core concepts:* Component nesting, passing data via React `props`, and array transformations.
*   **`unicafe/`** (Exercises 1.6 - 1.11)
    *   A real-time customer feedback app that collects metrics (*Good*, *Neutral*, *Bad*) and computes operational statistics.
    *   *Core concepts:* Multiple state fields, complex mathematical calculations on-the-fly, conditional rendering, and structured HTML table layout components.
*   **`anecdotes/`** (Exercises 1.12 - 1.14)
    *   An interactive dashboard displaying software development quotes with a dynamic voting mechanism.
    *   *Core concepts:* React state initialization using dynamic array allocations (`new Array().fill(0)`), array cloning with the JavaScript spread operator `[...state]` to protect state immutability, and calculating derivative data cleanly during re-renders (`Math.max`).

## 🛠️ Main Tech Stack

*   **Library:** [React](https://react.dev) (Functional Components)
*   **State Control:** React `useState` hooks
*   **Syntax:** JSX & ES6+ JavaScript
*   **Build Tooling:** [Vite](https://vite.dev) 

## 📋 Key Learning Takeaways

1.  **Component Architecture:** Designing modular, single-responsibility React functional components.
2.  **Unidirectional Data Flow:** Passing dynamic configuration values and callback handlers downwards from parent components down to child sub-elements via `props`.
3.  **State Immutability:** Learning to always treat React state arrays and objects as read-only, mutating copies to safe-guard stable component lifecycles.
4.  **Re-rendering Mechanics:** Understanding exactly how event handlers capture user inputs and trigger interface updates efficiently.

---
*Developed as educational coursework for the University of Helsinki Open University.*
