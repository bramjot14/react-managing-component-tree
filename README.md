# React To-Do List – Managing a Component Tree

This project is a simple React To-Do List built to practice managing a component tree, lifting state up, and passing data between parent and child components using props.

## 🚀 Concepts Practiced

- Component hierarchy (parent → child)
- Passing functions as props
- Lifting state up to the parent component
- Updating state immutably using `useState`
- Handling events in child components
- Removing items from a list using `filter`
- Controlled input fields

## 🧠 How It Works

- The `App` component holds the main state:
  - `inputText` for the input field
  - `items` for the list of todos
- Each todo item is rendered using a `ToDoItem` child component
- When a todo item is clicked:
  - The child calls a function passed from the parent
  - The parent removes the item from state
  - React re-renders the updated list

## 🛠 Tech Stack

- React
- JavaScript (ES6)
- CSS
- JSX

## 📦 Project Structure

src/
├── App.jsx
├── ToDoItem.jsx
├── index.js
└── styles.cs


## ✅ Learning Outcome

This project helped solidify the core React pattern of **unidirectional data flow**, where data flows down via props and actions flow up via callback functions.

---
