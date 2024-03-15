# Blog App (Initial Phase)

Welcome to the Blog App, a simple blogging platform built with React, Appwrite, and other technologies. This project is currently in its initial phase and serves as a starting point for developing a full-fledged demo blogging application.

## Features (planned)

- User registration and authentication
- Create, edit, and delete blog posts
- Comment on blog posts
- User profile pages
- User-friendly UI and responsive design
- Search functionality
- Post likes
- And much more!

## Getting Started

1. **Clone this repository** to your local machine.
2. **Install dependencies** by running `pnpm install`.
3. **Configure Appwrite**: Update the `appwriteConfig.js` file.
4. **Run the development server** with `pnpm run dev`.

Please note that this project is a work in progress, and additional features and improvements will be added in subsequent phases.

## Contribution

Contributions are welcome! If you'd like to contribute to the development of this project, please open an issue or submit a pull request.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **Appwrite**: An open-source platform for building powerful backend applications.
- **Redux Toolkit**: A set of tools to manage state in React applications.
- **React Router DOM**: Declarative routing for React applications.
- **Tailwind CSS**: A utility-first CSS framework for quickly building custom designs.
- **TinyMCE React**: A rich text editor component for React applications.
- **TypeScript**: A superset of JavaScript that adds static types to the language.

## Package.json Configuration

```json
{
  "name": "blogwithreact",
  "private": true,
  "version": "0.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "tsc && vite build",
    "lint": "eslint . --ext ts,tsx --report-unused-disable-directives --max-warnings 0",
    "preview": "vite preview"
  },
  "dependencies": {
    "@reduxjs/toolkit": "^1.9.6",
    "@tinymce/tinymce-react": "^4.3.0",
    "appwrite": "^13.0.0",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-hook-form": "^7.47.0",
    "react-redux": "^8.1.3",
    "react-router-dom": "^6.16.0"
  },
  "devDependencies": {
    "@types/react": "^18.2.15",
    "@types/react-dom": "^18.2.7",
    "@typescript-eslint/eslint-plugin": "^6.0.0",
    "@typescript-eslint/parser": "^6.0.0",
    "@vitejs/plugin-react": "^4.0.3",
    "autoprefixer": "^10.4.16",
    "daisyui": "^3.8.3",
    "eslint": "^8.45.0",
    "eslint-plugin-react-hooks": "^4.6.0",
    "eslint-plugin-react-refresh": "^0.4.3",
    "postcss": "^8.4.31",
    "tailwindcss": "^3.3.3",
    "typescript": "^5.0.2",
    "vite": "^4.4.5"
  }
}
