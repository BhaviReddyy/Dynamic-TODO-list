# Dynamic-TODO-list

This project implements a dynamic To-Do List using JavaScript and DOM manipulation.  
Users can add tasks, mark them as complete, and delete them.

## 📌 Features Implemented

### ✔ 1. Add New Tasks
- User enters a task in the input field.
- Clicking **"Add Task"**:
  - Adds a new `<li>` item to the task list.
  - Prevents empty tasks from being added.
  - Clears the input field after adding.

### ✔ 2. Complete a Task
- Each task has a **"Complete"** button.
- When clicked, it:
  - Crosses out the task (`line-through`)
  - Changes the text color to gray
  - Marks it visually as done.

### ✔ 3. Delete a Task
- Each task has a **"Delete"** button.
- Removes the task completely from the list.

### ✔ 4. Robust Error Handling
- Prevents adding empty tasks.
- Each task is dynamically created with its own buttons and event listeners.

---

## 📂 Files Included
- `index.html` — Contains the app layout.
- `script.js` — Contains all dynamic DOM logic and event handling.

---

## 🚀 How to Run
1. Open `index.html` in any browser.
2. Type a task and click **Add Task**.
3. Use **Complete** and **Delete** buttons for each task.

---

## 🛠 Technologies Used
- HTML  
- JavaScript (DOM Manipulation, Event Handling)
