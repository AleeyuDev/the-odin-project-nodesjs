
# Basic Express.js Website

A simple Node.js web application built with Express.js that serves static HTML pages.

## Features

- Simple routing system
- Static HTML pages
- Contact form page
- Custom 404 error page
- Environment variable support

## Project Structure

```
├── index.js         # Main application entry point
├── index.html       # Home page
├── about.html       # About page
├── contact-me.html  # Contact page
└── 404.html         # Error page
```

## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Create a `.env` file with your port configuration:
```
PORT=3000
```

3. Start the development server:
```bash
npm run server
```

The application will be available at `http://localhost:3000`

## Routes

- `/` - Home page
- `/about` - About page
- `/contact-me` - Contact form
- All other routes will redirect to 404 page

## Tech Stack

- Node.js
- Express.js
- dotenv (for environment variables)
- nodemon (for development)
