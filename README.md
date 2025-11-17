# MindSpark - Interactive Quiz Platform

This is a web-based quiz application built as a non-syllabus project. It is a feature-rich, frontend-only application that runs entirely in the browser, using `localStorage` to manage all user data, quizzes, and scores.

## Project Overview

"MindSpark" is a single-page application (SPA) that provides a complete quiz ecosystem without any backend. It is designed to be a professional, polished, and engaging platform for creating and taking quizzes.

## Core Features

* **Full User System:** Local registration and login system with a persistent logged-in state.
* **User Dashboard:** A central hub for users to see their created quizzes and score history.
* **Advanced Quiz Maker:**
    * Create quizzes with titles and time limits.
    * Supports Multiple Choice, True/False, and Fill-in-the-Blank questions.
    * **"Test Mode"** option to hide instant feedback for serious assessments.
    * **Edit Quiz** functionality to load a saved quiz back into the maker.
    * **Delete Quiz** functionality.
* **Interactive Quiz Player:**
    * A clean, timed interface for taking quizzes.
    * "Practice Mode" with instant sound and color feedback.
* **User Profiles:** A dedicated page with calculated stats like "Average Score," "Quizzes Taken," and "Quizzes Created," including a chart for recent scores.
* **Sharing & Data Management:**
    * **Share by Link:** Generates a unique URL that encodes the entire quiz, allowing it to be shared with anyone.
    * **Import/Export:** Allows users to save their quizzes as `.json` files for backup or to import quizzes from others.
* **Modern UI/UX:**
    * Fully responsive design for desktop and mobile.
    * **Light/Dark Mode** toggle with user preference saved locally.
    * Clean, modal-based navigation with "X" close buttons on all popups.

## Technology Used

* **HTML5:** For the structure of the application.
* **CSS3 (with Tailwind CSS):** For all styling, layout, responsiveness, and the theme-toggling system.
* **JavaScript (ES6+):** For all application logic, including:
    * DOM manipulation (showing/hiding pages).
    * Event handling.
    * All quiz player and scoring logic.
    * Data persistence using the Web Storage API (`localStorage`).
    * Base64 encoding/decoding for the "Share by Link" feature.
* **Feather Icons:** For a clean, lightweight icon set.