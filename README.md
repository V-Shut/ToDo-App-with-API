# [Preview](https://v-shut.github.io/ToDo-App-with-API/)

This project is a React and TypeScript-based Todo List application that allows users to manage their tasks efficiently. The app supports essential functionalities such as adding new tasks, marking tasks as complete, deleting tasks, and filtering tasks based on their completion status (All, Active, Completed).

# Key Features:
- Add New Todos: Users can add new tasks by typing in the input field and pressing Enter. The tasks are temporarily stored and displayed instantly while waiting for the server response.
- View Todos: The tasks are displayed in a list, with the ability to view all tasks, active tasks, or completed tasks based on the selected filter.
- Update Todo Status: Users can toggle the completion status of individual tasks by clicking the checkbox next to each task or toggle all tasks at once using the "Toggle All" button.
- Edit Todos: Users can edit the title of an existing task by double-clicking on it, changing the text, and pressing Enter or clicking outside the input field to save the changes.
- Delete Todos: Tasks can be removed individually by clicking the delete button next to each task, or all completed tasks can be deleted at once using the "Clear Completed" button.
- Error Handling: The app gracefully handles errors such as failed requests when performing CRUD operations and displays error notifications to the user.

# Architecture:
- React Components: The application is built using functional components and hooks (useState, useEffect). Components such as Header, TodoList, Footer, and Errors are organized to manage different parts of the UI.
- State Management: The component state is used to manage the list of tasks (todosList), filter options, and temporary states for tasks being edited or deleted.
- API Integration: The application interacts with an external API for CRUD operations (Create, Read, Update, Delete) on the tasks. The API responses are used to update the UI accordingly.

# Error Handling:
- The application has built-in error handling to manage different types of errors, such as loading errors, deletion errors, and update errors. Errors are displayed to users in a non-intrusive manner and automatically dismissed after a few seconds.

# Utilities:
- Filtering: A utility function, filterTodos, is used to filter tasks based on the selected filter (All, Active, Completed).
- Server Requests: API requests are abstracted into functions that handle the interaction with the backend, providing a clean and modular approach to handling server data.

# How to use:
Project Interaction Instructions
This project is a React TypeScript starter pack, including setup for ESLint, Prettier, and Bulma for styling.

Cloning the Repository:
1. To get started, clone the repository:
- git clone
- cd react-typescript-starter-pack
  
2. Installing Dependencies
After cloning, install the required dependencies:
- npm install
  
3. Running the Project in Development Mode
To run the project in development mode, use:
- npm start (This will open your project in the default web browser.)
  
4. Building the Project for Production
To build the project for production, run:
- npm run build (This will create an optimized version of your app in the build folder.)
5. Deploying to GitHub Pages
To deploy to GitHub Pages, use the following commands:
- npm run deploy
  
6. Linting and Formatting Code
To check and automatically fix code style issues, use:
- npm run lint
  
7. To format TypeScript files with Prettier, run:
- npm run format
