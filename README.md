# React Movie Search Engine App

This repository contains a React-based Movie Search Engine application. This project demonstrates the implementation of core React concepts by integrating with The Movie Database (TMDB) API to fetch and display comprehensive movie information. The application provides users with the ability to discover popular films, search for specific movie titles, and manage a personalized list of favorite movies.

You can vist the website [**Here**](https://n8el.github.io/React-Movie-App/)

---

## Features

* **Popular Movie Display:** Precents a curated list of currently popular films upon application load.
* **Dynamic Search Functionality:** Enables users to search for movies by title, providing real-time results.
* **Favorites Management:** Allows users to add or remove movies from a personal favorites collection.
* **Persistent Favorites:** Utilizes browser's Local Storage to ensure favorite selections persist across sessions.
* **Intuitive Navigation:** Implements client-side routing for seamless transitions between the main movie listing and the favorites page.

---

## 🚀 Technologies and Libraries

This project is built using a modern React development stack:

* **React:** The primary JavaScript library for constructing dynamic user interfaces.
* **Vite:** A next-generation frontend tooling that provides a fast development environment and optimized build process.
* **The Movie Database (TMDB) API:** An external RESTful API used for retrieving movie data.
* **React Router DOM:** A collection of navigational components that enable declarative routing in React applications.
* **React Context API:** Employed for efficient global state management, specifically for handling the favorites list across various components without prop drilling.
* **`useState` Hook:** Manages component-specific state, including form inputs, loading indicators, and movie data.
* **`useEffect` Hook:** Handles side effects such as data fetching, subscriptions, and manual DOM manipulations.
* **Local Storage:** A web storage API used for client-side data persistence of user preferences (e.g., favorite movies).
* **CSS:** Utilized for styling the application, ensuring a responsive and visually appealing user experience.

---

## 🛠️ Getting Started

To set up and run this project on your local machine, please follow these instructions:

1.  **Clone the repository:**
    ```bash
    git clone <repository-url> # Replace with your actual repository URL
    cd <repository-name>
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Start the development server:**
    ```bash
    npm run dev
    ```
    The application will typically be accessible in your web browser at `http://localhost:5173/` (or a similar address provided in your terminal).

---
