# 🛒 Grocery Store Web Application

A full-stack **Grocery Store Management System** built with **Python (Django framework)**.  
This project provides a complete e-commerce style platform where users can browse groceries, manage carts, place orders, and admins can manage products, categories, and users.

---

## 🚀 Features

### 👤 User Side
- User registration & authentication (signup, login, logout, password reset)
- Browse grocery items by category
- Add/remove items from the shopping cart
- Place orders and view order history
- Upload & manage profile details

### 🛠️ Admin Side
- Secure admin dashboard
- Manage users (customers & staff)
- Add, edit, delete grocery items
- Manage product categories
- View orders and user activities

---

## 🏗️ Tech Stack

- **Backend**: Python, Django
- **Frontend**: HTML, CSS, Bootstrap, Django Templates
- **Database**: SQLite (default) / PostgreSQL (for production)
- **Deployment Ready**: Configured with `Procfile` and `runtime.txt` for **Heroku**

---
Grocery/
│── core/ # Core Django app
│── ecomprj/ # Project configurations
│── userauths/ # User authentication system
│── useradmin/ # Admin panel features
│── templates/ # HTML templates
│── static/ # CSS, JS, images
│── media/ # Uploaded media files
│── db.sqlite3 # Default SQLite DB
│── manage.py # Django management script
│── requirements.txt # Dependencies
│── Procfile # For deployment (Heroku)
│── runtime.txt # Python runtime version

## 📂 Project Structure

## ⚙️ Installation & Setup

Follow these steps to run the project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Ashwinlaralewis/Grocery.git
cd Grocery
2️⃣ Create Virtual Environment
bash
Copy code
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
3️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
4️⃣ Run Database Migrations
bash
Copy code
python manage.py makemigrations
python manage.py migrate
5️⃣ Create Superuser
bash
Copy code
python manage.py createsuperuser
6️⃣ Run Development Server
bash
Copy code
python manage.py runserver
Now open http://127.0.0.1:8000 🎉



