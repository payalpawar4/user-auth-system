🔐 Django User Authentication System

A simple and clean Django-based user authentication system with login and logout functionality. Ideal for beginner to intermediate developers learning Django and building secure web apps.

---

## 📂 Project Features

- Django user login system with session-based authentication  
- CSRF protection on forms  
- Bootstrap 5 styled responsive UI  
- Secure `.env` handling for sensitive data like secret keys  
- Custom login form with "Remember Me" checkbox  
- Logout functionality  
- Modular file structure

---

## 🚀 Tech Stack

- **Backend**: Django 5.2.3 (Python 3.12)
- **Frontend**: HTML, CSS, Bootstrap 5
- **Database**: SQLite (default)

---

## 📁 Folder Structure

userproject/
├── home/
│ ├── views.py
│ ├── urls.py
│ └── templates/
│ ├── index.html
│ └── login.html
├── userproject/
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
├── static/
├── templates/
├── db.sqlite3
├── .env
├── .gitignore
└── manage.py

## 🛠️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/payalpawar4/user-auth-system.git
cd user-auth-system

2. Create and Activate a Virtual Environment

bash
python -m venv env
env\Scripts\activate  # For Windows
# OR
source env/bin/activate  # For Mac/Linux

3. Install Dependencies

bash
pip install -r requirements.txt

If you don’t have requirements.txt, install manually:

bash
pip install django python-decouple

4. Create .env File
In the root folder (where manage.py is), create a .env file:

env
SECRET_KEY=your-secret-key-here
DEBUG=True

5. Run the Server

bash
python manage.py runserver

Visit http://127.0.0.1:8000 in your browser.

🧪 Default Test Credentials
Use this pre-created user to log in:

Username: payal
Password: payal@0401

✅ .gitignore Settings
Your .gitignore should include:

bash
Copy code
__pycache__/
*.pyc
db.sqlite3
/static/
.env
.env.*

🪪 License
This project is licensed under the MIT License. See the LICENSE file for details.

✨ Author
Made with ❤️ by Payal Pawar
🔗 GitHub

🙋‍♀️ Want to Contribute?
Pull requests are welcome! For major changes, open an issue first to discuss what you’d like to change.

Let me know if you want to customize it more — e.g. add screenshots, GitHub badges, or deployment instructions.
