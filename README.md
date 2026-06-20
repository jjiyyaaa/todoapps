#TodoApps — Simple Todo List Web App

- **Description:** A lightweight, client-side Todo application that lets you add tasks with due dates, mark them complete, undo completed tasks, and remove tasks. Data persists in the browser using Local Storage so your list survives page reloads.

##Key Features

- **Add Tasks:** Create new todos with a title and a due date.
- **Mark Complete / Undo:** Move tasks between pending and completed lists.
- **Delete Tasks:** Remove tasks permanently.
- **Persistence:** All todos are stored in the browser via `localStorage`.
- **Simple UI:** Clean, minimal interface built with HTML/CSS and vanilla JavaScript.

##Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (ES6)

##Getting Started / Installation

Prerequisites: a modern web browser. Optional: a static file server for local testing.

1. Clone the repository (or download the ZIP) and open the `todoapps` folder:

```bash
git clone <repo-url>
cd repo-name/todoapps
```

2. Run locally:

- Open the file [todoapps/index.html](todoapps/index.html) directly in your browser.
- Or serve the folder with a simple static server:

```bash
# Python 3
python -m http.server 8000
# or using Node (http-server)
npx http-server . -p 8000
```

Then open `http://localhost:8000` in your browser.

##Usage

- Fill the form at the top to add a new todo (title and due date) and click **Submit**.
- New todos appear under **Yang harus dilakukan** (Pending). Click the check button to mark a task as completed.
- Completed tasks appear under **Yang sudah dilakukan** (Completed). Use the undo button to restore a task or the trash button to delete it.
- The app shows a small alert whenever changes are saved to localStorage.

##Important Files

- [todoapps/index.html](todoapps/index.html) — Main HTML file.
- [todoapps/css/style.css](todoapps/css/style.css) — Styles and layout.
- [todoapps/js/script.js](todoapps/js/script.js) — Application logic (add/complete/delete/persistence).

##Notes & Contribution

- This project uses only client-side technologies and requires no build step.
- Contributions, improvements, or translations are welcome — open a pull request with suggested changes.
