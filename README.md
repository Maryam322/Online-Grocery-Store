#  Online Grocery Store

A responsive **online grocery store web application** built with **Python and Django**. Users can browse products, search and filter groceries, manage their cart, place orders, and view order history.

##  Features

*  User Registration & Authentication
*  Product & Category Management
*  Product Search, Filtering & Sorting
*  Session-Based Shopping Cart
*  Checkout & Order Management
*  User Profile & Order History
*  Customized Django Admin Dashboard
*  Inventory & Order Management
*  CSV Product Import
*  Responsive Bootstrap UI

##  Tech Stack

* **Backend:** Python, Django 5.2
* **Frontend:** HTML, CSS, Bootstrap 5, Django Templates
* **Database:** SQLite
* **Images:** Pillow
* **Icons:** Bootstrap Icons

##  Installation

```bash
git clone https://github.com/Maryam322/Online-Grocery-Store.git
cd Online-Grocery-Store
```

Extract `backend.zip` and `frontend.zip`, then navigate to the Django project:

```bash
cd backend/backend
```
Create and activate a virtual environment:

```bash
python -m venv venv
venv\Scripts\activate
```

Install dependencies:

```bash
pip install Django==5.2.8 Pillow
```

Run migrations:

```bash
python manage.py migrate
```
Create an admin account:

```bash
python manage.py createsuperuser
```

Start the server:
```bash
python manage.py runserver
```
Open:
```text
http://127.0.0.1:8000/
```
##  Admin Panel
*   **URL**: [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)
*   **Username**: `admin`
*   **Password**: ` `

##  Main Pages

* `/` — Home
* `/products/` — Products
* `/cart/` — Shopping Cart
* `/order/create/` — Checkout
* `/orders/` — Order History
* `/profile/` — User Profile
* `/admin/` — Admin Dashboard

##  Future Improvements

* PostgreSQL integration
* Online payment gateway
* Product reviews & ratings
* Wishlist
* Order tracking
* Django REST API
* Email notifications

##  Author

**Maryam Fatima**

GitHub: [Maryam322](https://github.com/Maryam322)
## 🛠️ Common Commands
*   **Create a new Admin**: `python create_superuser.py`
*   **Reset Database** (if needed): Delete `db.sqlite3` and run `python manage.py migrate`
