# ✅ React To-Do List App

A simple and functional **To-Do List application built with React** that allows users to add, edit, complete, and delete tasks. This project focuses on core React concepts like state management, props, conditional rendering, and component-based architecture.

---

## 🚀 Features

- ➕ Add new tasks  
- ✏️ Edit existing tasks  
- ✅ Mark tasks as completed  
- 🗑️ Delete tasks  
- 🎯 Unique task IDs using UUID  
- 🎨 Icons using Font Awesome  
- ⚛️ Fully component-based React architecture  

---

## 🧠 Concepts Used

- React Functional Components  
- `useState` Hook  
- Props & Parent–Child Communication  
- Conditional Rendering  
- Event Handling  
- Array methods (`map`, `filter`)  
- Controlled Components  
- UUID for unique keys  

---

## 🛠️ Tech Stack

- React (Create React App)
- JavaScript (ES6+)
- CSS
- UUID
- Font Awesome

---

## 📂 Project Structure

```
src/
│
├── components/
│   ├── Todo.js
│   ├── TodoForm.js
│   ├── EditTodoForm.js
│   └── TodoWrapper.js
│
├── App.js
├── App.css
└── index.js
```

---

## ⚙️ Installation & Setup

1. Clone the repository
```bash
git clone https://github.com/your-username/react-todo-app.git
cd react-todo-app
```

2. Install dependencies
```bash
npm install
```

3. Install required packages
```bash
npm install uuid
npm install @fortawesome/react-fontawesome
npm install @fortawesome/free-solid-svg-icons
```

4. Start the development server
```bash
npm start
```

The app will run at:  
`http://localhost:3000`

---

## 🧩 How It Works

- **TodoWrapper**  
  Manages the main `todos` state and contains logic for adding, editing, deleting, and completing tasks.

- **TodoForm**  
  Handles user input for adding new tasks.

- **Todo**  
  Displays individual tasks with complete, edit, and delete actions.

- **EditTodoForm**  
  Allows updating an existing task when edit mode is enabled.

State is lifted to the parent component so multiple child components can access and modify it via props.

---

## 📸 App Functionality

- Type a task and press **Enter** or click **Add Task**
- Click on a task to mark it **completed**
- Click ✏️ to **edit** a task
- Click 🗑️ to **delete** a task

---

## 🎯 Future Improvements

- Persist todos using `localStorage`
- Add drag-and-drop support
- Add task priorities or due dates
- Improve UI with animations

---

## 🙌 Acknowledgements

Built as a practice project to strengthen React fundamentals and component-based development.

⭐ If you like this project, consider starring the repository!
