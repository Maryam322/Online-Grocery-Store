# Online Grocery Store

A robust e-commerce platform for selling grocery items, built with Django.

## 🚀 How to Run (VS Code)

### 1. Prerequisites
Ensure you have **Python** installed on your computer.

### 2. Setup (One-time)
Open the terminal in VS Code (Ctrl+`) and make sure you are in the `online_grocery_store` folder where `manage.py` is located.

1.  **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

### 3. Run the Server
To start the website, run this command:

```bash
python manage.py runserver
```

*   You will see a link like `http://127.0.0.1:8000/`. Ctrl+Click it to open the website.
*   To stop the server, press `Ctrl+C` in the terminal.

## 🔑 Admin Panel
*   **URL**: [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)
*   **Username**: `admin`
*   **Password**: ` `

## 🛠️ Common Commands
*   **Create a new Admin**: `python create_superuser.py`
*   **Reset Database** (if needed): Delete `db.sqlite3` and run `python manage.py migrate`
