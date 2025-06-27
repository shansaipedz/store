# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
Here is a **GitHub README-style description** for your React project using a filterable product table with search functionality:

---
# 🔍 React Filterable Product Table

## Description

This is a **React-based** web application that demonstrates a classic **filterable product table** pattern. Users can search through a list of products and filter them dynamically by typing into a search bar. The project highlights core concepts in modern React development such as **component composition**, **prop drilling**, and **state lifting**.

The main components include:

* `SearchBar`: Captures user input for filtering.
* `ProductTable`: Displays the product list according to the filter.
* `FilterProductTable`: Acts as a container and manages state across child components.

This is a foundational project often used in tutorials to teach how data flows in React, especially with parent-child relationships and real-time UI updates.

## Features

* 🔎 Live product filtering as you type
* 🧱 Modular, reusable components
* ⚛️ Built with React functional components and hooks
* 🎨 Styled with custom CSS (`App.css` and `index.css`)
* 🧪 Simple and extendable structure — great for learning or prototyping

## Technologies Used

* React.js (Vite + JSX)
* JavaScript (ES6+)
* CSS Modules (`App.css`, `index.css`)

## Folder Structure

```bash
.
├── App.jsx              # Main component that renders the filterable table
├── main.jsx             # Entry point rendering the App
├── App.css              # App-level styling
├── index.css            # Global and base styles
└── components/
    ├── FilterProductTable.jsx
    ├── ProductTable.jsx
    └── SearchBar.jsx
```

## Getting Started

1. Clone this repository
2. Install dependencies:

   ```bash
   npm install
   ```
3. Run the development server:

   ```bash
   npm run dev
   ```
4. Open your browser at [http://localhost:5173](http://localhost:5173)

## Learning Objectives

* Understand component hierarchy and prop passing
* Practice state lifting and controlled components
* Improve UI interactivity using real-time filtering
* Build a clean, responsive React application structure

---
