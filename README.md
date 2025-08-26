# 📝 To-Do App

A simple and intuitive **Task Management Web Application** built with **Django**.
This app allows users to **add, view, and manage tasks** easily — helping you stay organized and productive.

---

## 🚀 Features

* ➕ Add new tasks
* ✅ Mark tasks as completed / uncompleted
* 🗑️ Delete tasks (coming soon)
* 📅 Automatic timestamp (created & updated)
* 🌈 Simple and clean UI

---

## 🛠️ Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML, CSS (Django Templates)
* **Database:** SQLite (default, can be switched to PostgreSQL/MySQL)
* **Version Control:** Git & GitHub

---

## ⚙️ Installation & Setup

Follow these steps to run the project locally:

```bash
# Clone the repository
git clone https://github.com/your-username/To-Do-App.git
cd To-Do-App

# Create a virtual environment
python -m venv env
env\Scripts\activate   # On Windows
# OR
source env/bin/activate  # On Mac/Linux

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the development server
python manage.py runserver
```

Now open 👉 **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)** in your browser.

---

## 🗂️ Project Structure

```
To-Do-App/
│── manage.py
│── db.sqlite3
│── tasks/          # App for managing tasks
│── templates/      # HTML templates
│── todo_main/      # Project settings
│── requirements.txt
│── README.md
```
## 🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License

This project is licensed under the **MIT License**.
