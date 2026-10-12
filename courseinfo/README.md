# Half Stack Application Development

A lightweight, component-based React application designed to display course information and track curriculum progress. This project demonstrates foundational React concepts, including component composition, structured data management, and data prop-drilling.

## Project Structure & Architecture

The application is structured into modular, reusable functional components:

*   **`App`**: Acts as the main controller. It manages the single data object containing the course name and an array of individual curriculum parts.
*   **`Header`**: Dynamically renders the name of the course.
*   **`Content`**: Orchestrates the display of the curriculum by mapping data arrays down to individual sub-components.
*   **`Part`**: A reusable presentational component that displays the specific name and exercise count for a given topic.
*   **`Total`**: Programmatically calculates and renders the cumulative sum of all exercises across the curriculum.

## Key Features

*   **Modular Component Design**: Built with clean, decoupled functional components following React best practices.
*   **Unified Data State**: Course data is encapsulated into a single JavaScript object, ensuring a predictable data structure.
*   **Dynamic Calculations**: Automatically computes the total number of exercises, eliminating hardcoded values in the UI layout.
