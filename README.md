# Blog Website with User Authentication

A Flask-based blog application that allows users to register, log in, and create blog posts. Built using Python, Flask, and SQLite, with a focus on clean code and simple user interface.

---

## ✨ Features

- 🧑‍💻 User registration and login
- 📝 Create, edit, and delete blog posts
- 📁 Stores data using SQLite database
- 🎨 Styled with HTML, CSS, and Flask templates
- 🔒 Form validation using Flask-WTF

---

## 🗂️ Project Structure


```markdown
blogs-website-with-user-authen/
├── main.py                 # Main Flask app
├── forms.py                # Flask-WTF form classes
├── requirements.txt        # Python packages
├── instance/
│   └── posts.db            # SQLite database
├── static/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── scripts.js
│   └── assets/
│       ├── favicon.ico
│       └── img/
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── make-post.html
│   ├── post.html
│   ├── about.html
│   ├── contact.html
│   ├── header.html
│   └── footer.html
└── .gitignore              # Git ignore rules

```


---

## 🛠️ How to Run

```bash
git clone https://github.com/Haridharan-k-0311/blogs-website-with-user-authen.git
cd blogs-website-with-user-authen
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python main.py
````

---

## 📌 Requirements

* Python 3.x
* Flask
* Flask-WTF
* SQLite

---

