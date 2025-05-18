
# 📝 FastAPI To-Do App with User Authentication

A simple To-Do List application built with **FastAPI**, **SQLAlchemy**, **JWT Authentication**, and **Jinja2 Templates**.

Users can:
- ✅ Register & log in
- 🔐 Get authenticated using JWT
- 🧾 Create, view, and delete personal to-dos

---

## 📦 Requirements

- Python 3.8+
- Virtualenv (recommended)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/vishnujee/TodoFast_api.git
cd todo-fastapi-app


#################

# Create venv
python -m venv venv

# Activate venv (Linux/macOS)
source venv/bin/activate

# Activate venv (Windows)
venv\Scripts\activate


pip install -r requirements.txt


todo_app/
├── models.py
├── main.py
├── database.py
├── schemas.py
├── auth.py
├── requirements.txt
├── README.md
└── templates/
    └── index.html

uvicorn main:app --reload
