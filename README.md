# 📝 Simple To-Do List Web App

A clean and responsive To-Do List application built with vanilla HTML, CSS, and JavaScript. This project demonstrates fundamental web development concepts including DOM manipulation, event handling, and dynamic UI updates.

## 🎯 Project Overview

This is a fully functional To-Do List web application where users can:
- ✅ Add new tasks
- ✔️ Mark tasks as complete/incomplete
- 🗑️ Delete tasks
- 🔄 Real-time UI updates without page reload

## 🛠️ Technologies Used

- **HTML5** - Structure and semantic markup
- **CSS3** - Styling and responsive design
- **Vanilla JavaScript** - Dynamic functionality and DOM manipulation

## 🚀 Features

### Core Functionality
- **Add Tasks**: Type in a task and click "Add Task" or press Enter
- **Complete Tasks**: Toggle completion status with visual feedback
- **Delete Tasks**: Remove unwanted tasks from the list
- **Empty State**: Friendly message when no tasks are present

### User Experience
- **Responsive Design**: Works on desktop and mobile devices
- **Keyboard Support**: Enter key to add tasks quickly
- **Visual Feedback**: Hover effects and color-coded states
- **Input Validation**: Prevents empty tasks from being added

## 📁 Project Structure

```
todo-list-app/
│
├── index.html          # Main HTML file with embedded CSS and JS
├── README.md          # Project documentation
└── screenshots/       # Output snapshots (add your images here)
```

## 🎨 Snapshots

![snapshotoftask](https://github.com/user-attachments/assets/8890c0bb-b65f-4feb-9032-8fa6977e2575)


## 💻 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/todo-list-app.git
   ```

2. **Navigate to project directory**
   ```bash
   cd todo-list-app
   ```

3. **Open in browser**
   - Double-click `index.html`, or
   - Use Live Server extension in VS Code, or
   - Serve with any local server

## 🎓 Learning Objectives

This project covers key web development concepts:

### JavaScript Concepts
- **DOM Selection**: `getElementById()`, `querySelector()`
- **Event Listeners**: Click events, keyboard events
- **Event Delegation**: Parent element handling child events
- **Array Methods**: `push()`, `filter()`, `find()`
- **ES6 Features**: `const`, `let`, arrow functions

### Web Development Skills
- **Dynamic Content**: Creating and removing HTML elements
- **State Management**: Tracking task completion status
- **User Interface**: Responsive design and user feedback
- **Best Practices**: Clean code structure and commenting

## 🔧 Code Highlights

### DOM Manipulation
```javascript
// Creating new task elements dynamically
function createTaskElement(task) {
    const listItem = document.createElement('li');
    listItem.className = 'task-item';
    // ... element creation and event binding
}
```

### Event Handling
```javascript
// Multiple event listeners for better UX
addButton.addEventListener('click', addTask);
taskInput.addEventListener('keypress', function(e) {
    if (e.key === 'Enter') addTask();
});
```

### State Updates
```javascript
// Toggle task completion with visual feedback
function toggleTaskComplete(taskId) {
    const task = tasks.find(t => t.id === taskId);
    task.completed = !task.completed;
    // Update UI accordingly
}
```



## 📚 Interview Questions Covered

This project demonstrates answers to common interview questions:

1. **DOM Selection**: Multiple methods shown (`getElementById`, `querySelector`)
2. **Event Listeners**: Click and keyboard event handling
3. **Event Delegation**: Parent container listening for child events
4. **Preventing Defaults**: Input validation and form handling
5. **Variable Declarations**: Usage of `var`, `let`, and `const`
6. **Event Bubbling**: Understanding event propagation
7. **Class Manipulation**: `classList.add()`, `classList.remove()`
8. **Closures**: Function scope and variable access
9. **Arrow Functions**: Modern JavaScript syntax
10. **Equality Operators**: Strict comparison with `===`
