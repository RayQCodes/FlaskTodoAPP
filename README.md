#  Flask To-Do App

A simple to-do list web application built using **Flask**, **SQLite**, and **SQLAlchemy**. You can add tasks, edit them, and delete them — all from your browser!

# Features

-  Add new tasks  
-  Edit existing tasks  
- Delete tasks  
-  Automatically saves the date a task was created  
-  Styled with SCSS  


## 🛠️ Technologies Used

- Python  
- Flask  
- Flask-SQLAlchemy  
- Flask-Scss  
- SQLite  
- Jinja2 (for templating)  

#PROJECT STRUCTURE: 

├── app.py             # Main Flask application
├── templates/         # HTML templates
│   ├── index.html
│   └── edit.html
├── static/            # Static files (e.g., SCSS/CSS)
├── project.db         # SQLite database
└── requirements.txt   # Python dependencies


# Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/flask-todo-app.git
cd flask-todo-app

# 2. Create a virtual environment (optional but recommended)
python -m venv venv
# On macOS/Linux
source venv/bin/activate
# On Windows
venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
python app.py

then it will direct you to go to a link : http://127.0.0.1:5000

