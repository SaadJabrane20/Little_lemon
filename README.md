# 🍋 Little Lemon Restaurant – Django Web Application

A Django-based full-stack web application built as part of the Coursera *Meta Backend Developer* specialization.  
The project simulates a real restaurant website where visitors can browse menu items, view item details, and make table reservations.

---

## 🚀 Features

### 🌐 Public Pages
- **Home Page** – General overview of the restaurant  
- **About Page** – Details about Little Lemon  
- **Menu Page** – Displays all menu items from the database  
- **Menu Item Detail Page** – Shows detailed information, price, and image of a selected dish  
- **Booking Page** – A form where users can reserve a table (stored in the DB)

### 🧩 Backend Features
- SQLite database using Django ORM  
- Dynamic pages rendered with Django Template Language (DTL)  
- CRUD-ready models for Menu and Bookings  
- Django `ModelForm` used to create bookings  
- URL routing with Django path converters  
- Template inheritance using `base.html`

---

## 📂 Project Structure

- **Little_lemon/**
  - **littlelemon/**  — main Django settings and configuration  
    - `__init__.py`  
    - `asgi.py`  
    - `settings.py`  
    - `urls.py`  
    - `wsgi.py`
  - **restaurant/**  — main application folder  
    - `__init__.py`  
    - `admin.py`  
    - `apps.py`  
    - `forms.py` *(Booking form — ModelForm)*  
    - `models.py` *(Menu & Booking models)*  
    - `urls.py` *(app-level URL routing)*  
    - `views.py`  
    - **templates/**  
      - `base.html`  
      - `index.html`  
      - `about.html`  
      - `menu.html`  
      - `menu_item.html`  
      - `book.html`
  - **static/**  — static files & images  
    - **img/**
      - **menu_items/**  
        - `*.jpg`
  - `db.sqlite3`  — SQLite database  
  - `manage.py`  
  - `README.md`




---

## 🛠 Technologies Used
- **Python 3**
- **Django 4+**
- **SQLite (default Django DB)**
- **HTML5 / CSS3**
- **Django Template Language (DTL)**

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/SaadJabrane20/Little_lemon.git
cd little_lemon
