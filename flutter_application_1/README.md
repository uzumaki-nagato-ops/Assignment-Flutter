# 📱 Flutter Personal Task Manager App

**Course:** Mobile App Development  
**Assignment:** Flutter Personal Task Manager Application  
**Framework:** Flutter  
**Backend / Database:** None  

---

## 📌 Project Overview

This is a **Personal Task Manager mobile application** developed using the **Flutter framework**.  
The application allows users to manage daily tasks by adding, viewing, completing, and deleting tasks.

All tasks are stored **temporarily in memory during runtime**.  
No backend service, database, or local storage is used, in accordance with the assignment requirements.

---

## ✨ Features

- Splash / Welcome Screen
- View list of tasks
- Add new tasks with:
  - Title
  - Description
  - Priority (Low, Medium, High)
- Mark tasks as completed
- Delete tasks with confirmation dialog
- View detailed information about each task
- Input validation using SnackBar messages
- Simple and clean user interface

---

## 🧭 Application Screens

The application consists of the following screens:

1. **Splash Screen** – Welcome screen with navigation to the Home screen  
2. **Home Screen** – Displays the list of tasks  
3. **Add Task Screen** – Allows users to add new tasks  
4. **Task Details Screen** – Displays full details of a selected task  

---

## 🔄 State Management

The application uses Flutter’s built-in state management:

- `StatefulWidget`
- `setState()`

Tasks are stored in a `List<Task>` during runtime.  
No backend service, database, or local storage is used.

---

## 🧪 Validation & User Experience

- Task title **must not be empty**
- SnackBar is used to display:
  - Validation errors
  - Task added confirmation
  - Task deleted confirmation
- AlertDialog is used for delete confirmation
- Task list updates instantly when tasks are added, deleted, or marked as completed

---

## 📸 Screenshots

All application screenshots are stored in:

```text
assets/screenshots/
