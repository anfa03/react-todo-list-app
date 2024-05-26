# todo-list App

A simple Todo application built with React and the Context API.

## Features

- Add new todos
- Mark todos as completed or active
- Filter todos by status (All, Active, Completed)
- Delete individual todos

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/anfa03/react-todo-list-app
```

2. Navigate to the project directory:

```bash
cd react-todo-list-app
```

3. Install dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm run dev
```

The app will be available at `http://localhost:5173/`.

## Usage

1. Enter a new todo in the input field and press Enter or click the "Add" button to add a new todo.
2. Click on a todo item to mark it as completed or active.
3. Click the "All", "Active", or "Completed" buttons to filter the todo list.
4. Click the Remove Button to remove a todo from the list.

## Project Structure

- `src/`
  - `components/`
    - `TodoForm.jsx`
    - `TodoList.jsx`
    - `TodoFilter.jsx`
    - `TodoItem.jsx``
  - `TodoProvider/`
    - `TodoContext.jsx`
  - `hooks/`
    - `useInput.js`
    - `useLocalStorage.js`
  - `App.jsx`
  - `index.css`
  - `main.jsx`
- `README.md`
- `package.json`
- `tailwind.config.js`

## Dependencies

- React
- React DOM
- Tailwind CSS

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open a new issue or submit a pull request.

```
## Author
Developed by Anfa Mohamed Hassan contact: anfacmohamed62@gmail.com
