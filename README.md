# Inventory Management System

This is a simple **Flask-based web application** to manage product inventories across multiple locations. It allows you to add products, define storage locations, track product movements, and generate inventory reports.

---

## Getting Started

### Step 1: Setup Project Folder

* Open **Visual Studio Code (VS Code)**.
* Create a new folder for the project, e.g., `inventory-app`.

---

### Step 2: Open Terminal

* Press \`Ctrl + \`\` in VS Code to open the integrated terminal.

---

### Step 3: Create Virtual Environment & Install Dependencies

Run the following commands in the terminal:

```bash
python -m venv venv
```

* On **Windows**, activate the virtual environment:

```bash
venv\Scripts\activate
```

* Then, install Flask and SQLAlchemy:

```bash
pip install flask flask-sqlalchemy
```

--- 

### Step 4: Project Structure

Your folder structure should look like this:

```
/inventory-app
├── app.py          # Main application file
├── models.py       # Defines the database schema using SQLAlchemy
├── templates/      # Jinja2 HTML templates
│   ├── base.html
│   ├── products.html
│   ├── locations.html
│   ├── movements.html
│   └── report.html
└── static/         # Static files like CSS, JavaScript, images
```

---

### Step 5: Run the Application

In the terminal, execute:

```bash
python app.py
```

---

### Step 6: Open the Application in Browser

Once the server is running, go to:

```
http://localhost:5000
```

You should see the Inventory Management dashboard.

---

## Features

* Add and manage **products**
* Define multiple **locations**
* Record **inventory movements**
* View inventory **reports**

---

## Technologies Used

* **Python**
* **Flask** – lightweight web framework
* **Flask-SQLAlchemy** – ORM for database management
* **HTML/CSS** – for frontend structure and styling

---


