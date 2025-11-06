# Task Manager Web App

A simple Task Manager application built with **Flask**, allowing users to create and manage tasks easily.  
This project is deployed for free using **Render**.

## 🚀 Live Demo
https://task-manger-ugu2.onrender.com/

---

## 🧰 Features
- Add new tasks
- View all tasks
- Clean and simple UI
- Flask backend with HTML templates

---

## 📂 Project Structure
```
project/
│
├── app.py
├── requirements.txt
├── Procfile
├── README.md
│
├── instance/
│   └── test.db              # SQLite database
│
├── static/
│   └── css/
│       └── main.css
│
└── templates/
    ├── base.html
    ├── index.html
    └── update.html
```


---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/task-manager.git
```
cd task-manager
2. Create Virtual Environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate   # On Linux / Mac
venv\Scripts\activate      # On Windows
```
3. Install Dependencies
```bash
pip install -r requirements.txt
```
4. Run the Application
```bash
python app.py
```

🤝 Contributing
Pull requests are welcome!
Feel free to fork this repo and improve UI / add features.

⭐ Show Support
If you like this project, give it a ⭐ on GitHub!