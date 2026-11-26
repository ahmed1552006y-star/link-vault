# Link Vault

A web application for saving, organizing, and managing links efficiently.

## Tech Stack & Libraries Purpose

- **react-router-dom**: Manages client-side routing and navigation between pages (such as Login, Dashboard, and link categories) without full-page reloads.
- **axios**: Handles HTTP requests to communicate with the backend API for fetching, creating, updating, and deleting links, including token attachment via interceptors.
- **zustand**: Provides lightweight global state management for authenticated user state, saved links list, and active search/filter states.
- **formik**: Manages form states, input handling, and submission workflows for adding/editing links and authentication forms.
- **yup**: Defines validation schemas integrated with Formik to enforce valid URL formats and required fields before submission.
- **tailwindcss**: Utility-first CSS framework configured with centralized design tokens in `src/index.css` to ensure consistent styling with zero hardcoded values.
- **react-icons**: Provides clean, scalable UI icons for actions like copying, editing, deleting, and categorizing links.