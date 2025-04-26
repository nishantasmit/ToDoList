This project is a simple and interactive **To-Do List application** developed using **React.js**. It allows users to manage their daily tasks easily by providing a clean and minimal interface.
Users can type a task into an input field and add it to the list by clicking a button. Each new task is immediately displayed below the input form without reloading the page, 
making the experience smooth and dynamic.

The application uses React's **`useState` hook** to manage two states — the current input text and the list of all added tasks. When a user types into the input field, 
the app captures the text in real-time and stores it in a state variable. Upon clicking the "Add" button, the entered text is added to the existing list of tasks while preserving the previous entries, 
thanks to the use of the **spread operator (`...`)**. After adding a task, the input field is cleared automatically, ready for the next task.

This To-Do List project demonstrates fundamental concepts of React, such as functional components, state management, event handling (`onChange`, `onClick`), and rendering lists using `map()`.
Although basic in functionality, it lays a strong foundation for more advanced features like deleting tasks, marking tasks as completed, or storing tasks persistently using local storage. 
Overall, it is an excellent beginner-friendly project that highlights how simple user interactions can be managed effectively with React.

