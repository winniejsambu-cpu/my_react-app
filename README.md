# My React App

A simple login interface built with React and Vite. The app provides a responsive sign-in form with email and password validation, a "Remember me" option, and a confirmation message after submission.

## Features

- Email and password inputs with required-field validation
- Remember-me checkbox
- Forgot-password link placeholder
- Client-side sign-in confirmation
- Responsive styling with custom CSS

> This is currently a front-end demonstration. It does not authenticate users or connect to a backend service.

## Getting Started

### Prerequisites

- Node.js 18 or newer
- npm

### Installation

Clone the repository, move into the project directory, and install dependencies:

```bash
npm install
```

### Development

Start the local development server:

```bash
npm run dev
```

Vite will print the local URL in the terminal, usually `http://localhost:5173`.

## Available Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run build` | Create a production build |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Check the code with Oxlint |

## Project Structure

```text
src/
├── components/
│   └── LoginPage.jsx  # Login form and submission state
├── App.jsx            # Application entry component
├── App.css            # Login page styles
├── index.css          # Global styles
└── main.jsx           # React and Vite bootstrap
```

## Built With

- [React](https://react.dev/)
- [Vite](https://vite.dev/)
- [Oxlint](https://oxc.rs/docs/guide/usage/linter)
