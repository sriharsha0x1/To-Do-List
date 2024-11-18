To-Do List Application

This is a simple and interactive To-Do List application built with HTML, CSS, and JavaScript. The app allows users to add, edit, and remove tasks easily, with data persistence enabled through `localStorage`.

Features

- Add Task:
 Users can add new tasks by entering text and either pressing the "Add" button or the "Enter" key.
- Edit Task:
 Users can modify existing tasks by clicking the "Edit" button next to each task.
- Remove Task:
 Users can delete individual tasks with the "Remove" button.
- Checkbox:
 A checkbox is provided for each task, allowing users to mark tasks as completed.
- Persistent Storage: Tasks are saved to the browser's `localStorage` to keep data across sessions.
  
 Code Explanation

HTML

The HTML file defines the basic structure of the app, including:
- An input field for adding tasks
- An "Add" button
- A task list area where tasks are displayed

 CSS

The CSS styles the app, providing a clean and modern interface using the Poppins font and flexbox for layout management.

 JavaScript

The JavaScript file contains the logic for managing the To-Do List:
- Adding Tasks: The `addTodo` function allows users to add tasks either by clicking the "Add" button or pressing "Enter."
- Editing Tasks: The `editTodo` function allows users to update the task content.
- Deleting Tasks: The `deleteTodo` function removes a task from both the display and `localStorage`.
- Saving to Local Storage: `localStorage` is used to save tasks so they persist across browser sessions.

 Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/sriharsha0x1/To-Do-List.git
