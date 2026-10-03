# reactjs-todo

A simple todo app built with React 19 and Vite. Add, edit, and delete tasks; the list persists in `localStorage` so it survives page reloads.

## Features

- Add / edit / delete todos
- `localStorage` persistence (loads saved todos on start)
- Component split: `Todoinput`, `TodoList`, `TodoCard`

## Stack

React 19, Vite 6, ESLint. No backend, no database.

## Run

```bash
npm install
npm run dev     # start dev server
npm run build   # production build
npm run lint    # eslint
```

## Files

- `src/App.jsx` - state, add/edit/delete handlers, `localStorage` sync
- `src/components/Todoinput.jsx` - new-task input
- `src/components/TodoList.jsx` - list rendering
- `src/components/TodoCard.jsx` - single row with edit/delete buttons
