# Todo List Application with Filtering Functionality

This project is a Todo List application built using React, with added functionality to filter tasks based on their completion status. Users can add new tasks, mark tasks as completed, remove tasks, and filter tasks based on their completion status.

## Features

- Add new tasks to the todo list.
- Mark tasks as completed or active.
- Remove tasks from the todo list.
- Filter tasks based on their completion status (All, Active, Completed).

## Setup

To run this project locally, follow these steps:

1. Clone the repository:


2. Open the index.html file in a web browser.

## Implementation Details

- The TodoApp component manages state using the useState hook to keep track of tasks, new task input, and the current filter.
- Tasks are stored as objects with properties for the task ID, text, and completion status.
- Users can add tasks by entering text in the input field and clicking the "Add Task" button.
- Tasks can be marked as completed or active by toggling the checkbox next to each task.
- Users can remove tasks by clicking the "Delete" button next to each task.
- Filtering functionality allows users to view all tasks, only active tasks, or only completed tasks.

## Observations and Learnings

- Enhanced understanding of React state management using the useState hook.
- Practiced handling user input, events, and dynamic rendering in React components.
- Gained insights into implementing filtering logic to display tasks based on their completion status.
- Learned to create a user-friendly interface for a Todo List application with filtering functionality.

## Challenges Faced

- Implementing the filtering functionality required careful consideration of state updates and conditional rendering to display the appropriate tasks.
- Managing the state of tasks, including their completion status and removal from the list, while ensuring smooth user interaction posed some challenges.

## Resources

- [React documentation](https://reactjs.org/docs/getting-started.html)
- [MDN Web Docs: HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs: JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

