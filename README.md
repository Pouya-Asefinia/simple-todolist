# Simple Todo List

A modern, clean, and interactive todo list application built with React and Vite. Features a beautiful gradient UI with Tailwind CSS styling and full CRUD functionality for managing your daily tasks.

## Features

- ✨ **Add Todos** - Create new tasks with a simple input field
- ✅ **Mark Complete** - Toggle the completion status of any task
- 🗑️ **Delete Todos** - Remove tasks you no longer need
- 📱 **Responsive Design** - Beautiful gradient background and card-based layout
- ⚡ **Fast & Lightweight** - Built with Vite for optimal performance
- 🎨 **Modern UI** - Styled with Tailwind CSS for a polished look

## Tech Stack

- **Frontend**: React 19
- **Build Tool**: Vite 7
- **Styling**: Tailwind CSS 4
- **Linting**: ESLint
- **Package Manager**: npm

## Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v16 or higher)
- npm (comes with Node.js)

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Pouya-Asefinia/simple-todolist.git
cd simple-todolist
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start the Development Server

```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or another port if 5173 is in use).

## Usage

### Adding a Todo
1. Type your task in the input field at the top
2. Click the "Add" button or press Enter
3. Your task will appear in the list below

### Marking a Todo as Complete
- Click the checkbox next to any task to toggle its completion status
- Completed tasks will appear with a strikethrough and gray text

### Deleting a Todo
- Click the red "Delete" button on the right side of any task to remove it permanently

## Available Scripts

- **`npm run dev`** - Start the development server with hot reload
- **`npm run build`** - Build the project for production (output in `dist/` directory)
- **`npm run preview`** - Preview the production build locally
- **`npm run lint`** - Run ESLint to check code quality

## Building for Production

To create a production-ready build:

```bash
npm run build
```

The optimized files will be generated in the `dist/` folder. You can then deploy this folder to any static hosting service.

To preview your production build locally:

```bash
npm run preview
```

## Project Structure

```
simple-todolist/
├── src/
│   ├── App.jsx          # Main application component
│   ├── main.jsx         # Entry point
│   └── index.css        # Global styles
├── index.html           # HTML template
├── package.json         # Project dependencies and scripts
├── vite.config.js       # Vite configuration
├── eslint.config.js     # ESLint configuration
└── README.md            # This file
```

## How It Works

The app uses React's `useState` hook to manage:
- **todos** - An array of todo objects with `id`, `text`, and `completed` properties
- **input** - The current value of the input field

### Key Functions

- **addTodo()** - Creates a new todo with a unique timestamp ID and resets the input
- **Toggle Complete** - Maps through todos and toggles the `completed` flag
- **Delete Todo** - Filters out the todo with the matching ID

## Contributing

Feel free to fork this project and submit pull requests for any improvements!

## Questions or Issues?

If you encounter any issues or have suggestions, please open an issue on the repository.

---

**Happy Todo-ing! 🚀**
