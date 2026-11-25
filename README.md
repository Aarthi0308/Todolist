# 📝 To-Do List Application

## 📌 About the Project
The To-Do List Application is a simple and user-friendly web application developed using HTML, CSS, and JavaScript. It helps users organize their daily activities by adding, completing, and deleting tasks.

## ✨ Features
- Add new tasks.
- Mark tasks as completed.
- Delete tasks.
- Add tasks using the Enter key.
- Save tasks using Browser Local Storage.
- Retain tasks even after refreshing the page.
- Display an empty message when there are no tasks.

## 🛠️ Technologies Used
- **HTML5** – Structure of the application.
- **CSS3** – Styling and layout.
- **JavaScript** – DOM manipulation and event handling.
- **LocalStorage** – Saving and retrieving tasks.

## 📂 Project Structure

```text
todo-app/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## ⚙️ How to Run the Project

1. Clone this repository:
   ```bash
   git clone YOUR_GITHUB_REPOSITORY_LINK
   ```
2. Open the project folder in VS Code.
3. Open `index.html` in your browser.
4. Start adding and managing your tasks.

## 💾 Data Persistence

The application uses browser LocalStorage to store tasks.

- `JSON.stringify()` converts the tasks array into a string before saving.
- `JSON.parse()` retrieves the saved string and converts it back into a JavaScript array.

This ensures that tasks remain saved even after the browser page is refreshed.

## 🎯 Learning Outcomes

- Understanding DOM manipulation.
- Handling click and keyboard events.
- Working with JavaScript arrays and objects.
- Using LocalStorage for data persistence.
- Managing application state in one place.

## 👩‍💻 Author

**Aarthi Ravikumar**

---

⭐ If you like this project, feel free to explore the repository!
