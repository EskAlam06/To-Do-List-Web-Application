# 📝 To-Do List Web Application

This is a simple and intuitive task management web application built using **Flask (Python)** for backend, **SQLite** for data storage, and **HTML/CSS** for the frontend. The application allows users to manage daily tasks by adding, editing, and deleting them with a clean, user-friendly interface.

---

## 🚀 Features

- ✅ Add New Task (with title and optional description)  
- 🖊️ Edit Existing Task  
- ❌ Delete Task  
- 📋 View Task List  

---

## 🔧 Tech Stack

| Component     | Tool/Framework         |
|---------------|------------------------|
| Backend       | Python (Flask)         |
| Frontend      | HTML/CSS               |
| Database      | SQLite (tasks.db)      |
| IDE           | PyCharm / VS Code      |
| Testing       | Chrome / Firefox       |
| OS            | Windows 10             |

---

## 📘 Project Goals

- Build a fully functional CRUD application using Flask.
- Create a user-friendly interface for managing tasks.
- Understand basic backend routing, database interaction, and UI behavior.
- Gain experience in stakeholder modeling for software testing contexts.

---

## 📌 Project Structure

/todo-app/
│
├── app.py # Main Flask app
├── templates/
│ ├── index.html # Task list display
│ └── edit.html # Task editing form
├── static/
│ └── style.css # Basic styling
├── tasks.db # SQLite database file
└── README.md # This file



---

## 💻 How to Run the Project

### Prerequisites
- Python 3.x installed
- Flask (`pip install flask`)

### Running the App

```bash
# Navigate to project folder
cd todo-app

# Run Flask server
python app.py

• Open your browser and visit: http://localhost:5000


🔁 Algorithms Summary
• Add Task: POST to /add, stored in SQLite, then redirect to index

• Edit Task: Pre-fill form, POST update, redirect with modified list

• Delete Task: Route /delete/<id> deletes task and reloads page

👤 Stakeholders
• Users: Add/edit/delete tasks

• Developers: Maintain backend logic and UI

• Testers: Validate task workflows

• Instructors: Assess code functionality and structure


📄 License

This project was developed for academic purposes.

