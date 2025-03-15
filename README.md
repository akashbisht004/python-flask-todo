# Flask TODO App

A simple TODO list application built with Flask and SQLite.

## Features
- Add new tasks
- View all tasks
- Update existing tasks
- Delete tasks
- Uses SQLite for database management

## Technologies Used
- **Backend:** Flask, SQLAlchemy
- **Frontend:** HTML, Jinja2, CSS
- **Database:** SQLite

## Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/akashbisht004/python-flask.git
cd flask-todo-app
```

### 2️⃣ Create & Activate Virtual Environment
```sh
# For Windows (Command Prompt)
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 4️⃣ Set Up the Database
```sh
python
>>> from app import db
>>> db.create_all()
>>> exit()
```

### 5️⃣ Run the Application
```sh
python app.py
```
Open your browser and go to `http://127.0.0.1:5000/`

## Folder Structure
```
flask-todo-app/
│-- static/        # CSS, JavaScript files
│-- templates/     # HTML templates (index.html, update.html, base.html)
│-- app.py         # Main Flask application
│-- requirements.txt # Dependencies
│-- README.md      # Project documentation
```

## API Endpoints
| Method | Endpoint         | Description               |
|--------|----------------|---------------------------|
| GET    | `/`            | Display all tasks         |
| POST   | `/`            | Add a new task            |
| GET    | `/delete/<id>` | Delete a task by ID       |
| GET/POST | `/update/<id>` | Update an existing task |

## Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

### 🚀 Happy Coding!

