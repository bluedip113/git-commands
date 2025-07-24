# git-commands


### 1. **Use `pipreqs` to create a `requirements.txt`**

   `pipreqs` is a tool that can automatically generate a `requirements.txt` file based on imports in your project files.

   - Install `pipreqs` if you haven’t:
     ```bash
     pip install pipreqs
     ```

   - Run `pipreqs` in the root directory of the project:
     ```bash
     pipreqs /path/to/your/project
     ```

### 2. **Set Up a Virtual Environment**
   Create a virtual environment to isolate the project dependencies.

   ```bash
   python -m venv env
   ```

   Then, activate the virtual environment:
   - On **Windows**:
     ```bash
     .\env\Scripts\activate
     ```


---

## ⚙️ 4. Run Migrations (to set up the database)

```bash
python manage.py migrate
```

---

## 👤 5. (Optional) Create Admin User

```bash
python manage.py createsuperuser
```

Follow the prompts to set up a login for the admin dashboard.

---

## 🚀 6. Run the Development Server

```bash
python manage.py runserver
```

You’ll see something like:

```
Starting development server at http://127.0.0.1:8000/
```

Open your browser and go to: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 📁 Optional Notes

* The project uses **SQLite** as its default DB (`db.sqlite3`).
* To upload or use media (like profile pictures), make sure the `media/` and `static/` directories are correctly served (already present here).
* Admin panel: [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)

---

Let me know if you want to **deploy it**, or connect to **PostgreSQL**, or add features!

