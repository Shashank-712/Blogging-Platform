# 📝 Blogging Platform

A simple and functional **Django-based blogging platform** built as a beginner project. It supports user authentication, post creation, and media uploads.

---

## 🚀 Features

- 👤 User Login & Logout
- ✍️ Create, Edit, and Delete Blog Posts
- 🖼️ Image Uploads (with media folder handling)
- 🗂️ Templating with Bootstrap for clean UI
- 🔐 Secure authentication & session management

---

## 🛠️ Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite (default for development)

---

## 📁 Project Structure:

Blogging Platform/
├── blog/ # Django app with models, views, urls, templates
├── templates/ # HTML templates
├── media/ # Uploaded images
├── .env/ # Virtual environment (not tracked)
├── manage.py # Django management script
└── db.sqlite3 # Development database


---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Shashank-712/Blogging-Platform.git
cd Blogging-Platform
```
2. Create & Activate a Virtual Environment
```
python -m venv .env
source .env/Scripts/activate   # On Windows
# or
source .env/bin/activate       # On Mac/Linux
```
3. Install Dependencies
```
pip install -r requirements.txt

```
(If requirements.txt is missing, you can create it with pip freeze > requirements.txt)
4. Run Migrations
```
python manage.py makemigrations
python manage.py migrate
```
5. Run the Server
```
python manage.py runserver
Visit http://127.0.0.1:8000/ in your browser to use the app.
```
📌 Notes
-All uploaded media will be stored in the media/ folder
-Database is SQLite for development purposes
-Environment variables and secret keys should be stored in .env (excluded via .gitignore)

🙌 Author
Made with 💻 by Shashank Rawat👹
👉 github.com/Shashank-712
