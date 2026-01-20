## 📌 Project Overview

This repository provides a **comprehensive introduction to RESTful APIs and Flask**, covering both **theoretical concepts** and **practical implementation**. It is designed for students, beginners, and interview preparation.

The content explains how to build, structure, and secure APIs using Flask, along with core web development features such as routing, templates, forms, sessions, and error handling.

---

## 🚀 Topics Covered

### 🔹 REST & API Fundamentals

* What is a RESTful API
* REST principles and architecture
* API specification (OpenAPI / Swagger)
* HTTP methods (GET, POST, PUT, DELETE, PATCH)
* HTTP status codes and their usage

### 🔹 Flask Basics

* Creating a basic Flask application
* Flask routing and URL mapping
* Handling GET and POST requests
* Using the request and response objects
* Returning JSON responses using `jsonify()`

### 🔹 Flask API Development

* Creating RESTful API endpoints
* Error handling (404, 500, custom errors)
* Securing Flask APIs (authentication, validation)
* Flask-RESTful extension
* API best practices

### 🔹 Database Integration

* Connecting Flask to SQL databases
* Flask-SQLAlchemy ORM
* Basic database operations

### 🔹 Flask Web Features

* Rendering HTML templates (Jinja2)
* Serving static files (CSS, JS, images)
* Handling forms and validating input
* Managing sessions
* Redirecting and URL generation with `url_for()`

### 🔹 Application Structure

* Using Flask Blueprints
* Organizing large Flask applications
* Custom Jinja filters

---

## 🛠️ Technologies Used

* **Python 3**
* **Flask**
* **Flask-SQLAlchemy**
* **Flask-RESTful**
* **Jinja2**
* **SQLite / MySQL (optional)**

---

## 📂 Project Structure (Example)

```
project/
│── app.py
│── models.py
│── routes/
│   ├── auth.py
│   ├── api.py
│── templates/
│── static/
│── requirements.txt
│── README.md
```

---

## ▶️ How to Run the Project

1. Clone the repository

```bash
git clone <repository-url>
```

2. Navigate to the project directory

```bash
cd project
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run the Flask application

```bash
python app.py
```

5. Open in browser
