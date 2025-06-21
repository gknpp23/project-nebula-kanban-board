# Interactive Kanban Dashboard

A fully interactive, responsive Kanban-style project management dashboard built from scratch with **pure HTML, CSS, and JavaScript**. This project serves as a demonstration of complex UI interactions, including drag-and-drop, resizable elements, and dynamic filtering, all implemented without any external JavaScript libraries.

![Screenshot do Dashboard Kanban](https://i.imgur.com/your-screenshot-url.png)

---

## ✨ Features

This project faithfully implements all requirements from the prompt:

* **Single Self-Contained File:** All code is bundled into a single `index.html` file for complete offline functionality.
* **Responsive Kanban Layout:** A classic Kanban board with "To Do," "In Progress," and "Done" columns that seamlessly stacks into a single column on mobile devices.
* **Glassmorphism Theme:** A sleek, dark-mode UI with translucent, blurred backgrounds and vibrant cyan/magenta accents.
* **Drag-and-Drop Widgets:** Users can intuitively drag and reorder task cards between different columns.
* **Resizable Widgets:** Each task card can be resized using a handle, demonstrating complex DOM manipulation.
* **Functional Ellipsis Menu:** Each card has a working menu with "Edit" and "Delete" actions.
* **Task Editing:** A modal window allows for editing the content of existing tasks.
* **Status Pill Filters:** Users can filter the visible tasks by their status (e.g., "Done", "In Progress").
* **Dark Mode Toggle:** A switch to alternate between the default dark theme and a light theme.
* **Custom UI Elements:** All elements, including menus and icons, are built with pure CSS and JavaScript, avoiding default browser styles.

## 🛠️ Tech Stack

* **HTML5** (Semantic structure)
* **CSS3**
    * CSS Grid for the main layout.
    * Custom Properties (Variables) for easy theming.
    * `backdrop-filter` for the Glassmorphism effect.
    * Advanced selectors and transitions for a polished user experience.
* **Vanilla JavaScript (ES6+)**
    * Drag and Drop API for reordering tasks.
    * DOM manipulation for resizing widgets and managing modals.
    * No external libraries or frameworks.

## 🚀 How to Use

As this is a single, self-contained file, no build process is needed.

1.  Clone this repository.
2.  Open the `index.html` file directly in any modern web browser.
3.  All features will work offline.

---

*This project was created as part of the Andromeda UI project, focusing on high-quality front-end development and strict adherence to technical requirements.*
