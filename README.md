# Expense Tracker – Django Web Application

## Project Description
The Expense Tracker is a web-based application developed using Django that allows users to record, manage, and track their daily expenses. The system supports user authentication and provides CRUD operations for expenses.

---

## Features
- User Registration and Login
- Secure Authentication using Django Auth
- Add, View, Edit, and Delete Expenses
- Category-based expense tracking
- Simple and user-friendly dashboard
- Session management and logout

---

## Technologies Used
- Python 3.10
- Django 5.2.9
- SQLite3
- HTML (Django Templates)

---

## How to Run the Project

### Step 1: Clone the Repository
```bash
git clone <your-github-repo-link>
cd ExpenseLearning
```

### Step 2: Create Virtual Environment
```bash
python -m venv myenv
myenv\Scripts\activate
```

### Step 3: Install Dependencies
```bash
pip install django
```

### Step 4: Apply Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### Step 5: Run the Server
```bash
python manage.py runserver

Open the browser and go to:

http://127.0.0.1:8000/
```

## How to create a Superuser
```bash
python manage.py createsuperuser

Enter the username, email, and password

Access it from - http://127.0.0.1:8000/admin/
```
