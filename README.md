# To-Do List App

This is a simple To-Do List application built with React. The app allows users to add, toggle, and delete tasks. It uses state management to keep track of the tasks.

## Features

- **Add Tasks**: Users can add new tasks to the to-do list.
- **Toggle Tasks**: Users can mark tasks as completed or uncompleted.
- **Delete Tasks**: Users can remove tasks from the list.
- **Task List Component**: The list of tasks is extracted into a separate `TaskList` component for better code organization.

## Getting Started

### Prerequisites

To run this project, you need to have Node.js and npm installed on your machine.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/alidaro/todo-list-app.git
    cd todo-list-app
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm start
    ```

The app should now be running on `http://localhost:3000`.

## Code Overview

### State Management

The app uses React's `useState` hook to manage the state of the to-do list. The state includes an array of task objects, each with an `id`, `text`, and `completed` status.

### Functions

- **handleAddTask**: Adds a new task to the state.
- **handleToggleTask**: Toggles the `completed` status of a task.
- **handleDeleteTask**: Removes a task from the state.

### Components

- **TaskList**: A component that renders the list of tasks. The tasks are passed to this component as props.

## Usage

1. **Add a Task**: Enter the task text in the input field and click the "Add" button.
2. **Toggle a Task**: Click on a task to mark it as completed or uncompleted.
3. **Delete a Task**: Click the "Delete" button next to a task to remove it from the list.

## Folder Structure


