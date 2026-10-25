# Filter React App

A React app for searching and filtering a produce list. Type to search by name, or use the dropdown to show only fruits or vegetables. The page also has a greeting component and a simple counter.

![React](https://img.shields.io/badge/React-18-20232A?logo=react&logoColor=61DAFB)
![Bootstrap](https://img.shields.io/badge/React_Bootstrap-7952B3?logo=bootstrap&logoColor=white)

## What it demonstrates

- **Class components** with local state (`FilteredList`, `Counter`)
- **Props**: data flows from `App` into `FilteredList` and then into `List`
- **Derived rendering**: the list is filtered on every render from the search text and the selected type, with no duplicated state
- **React Bootstrap** dropdown for the type filter

## Components

| Component | Role |
|---|---|
| `App` | Holds the produce data and lays out the page |
| `FilteredList` | Search box + type dropdown; filters items |
| `List` | Renders the filtered items |
| `HelloWorld` | Greeting that takes a `name` prop |
| `Counter` | Button that increments a count |

## Run it

```bash
npm install
npm start
```

Open http://localhost:3000.
