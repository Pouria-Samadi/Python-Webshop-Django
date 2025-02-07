```markdown
# 🛍️ Python Webshop - Django

A simple Django-based webshop where users can browse products, see prices, and add items to a cart. Built using **Django, Python, SQLite, and Bootstrap**.

## 📸 Screenshot
![PyShop Screenshot](https://raw.githubusercontent.com/Pouria-Samadi/Python-Webshop-Django/main/pyshop.jpg)

## 🚀 Features
- 🛒 Browse products with images and prices
- 📌 Add items to the shopping cart
- 🗄️ Uses **SQLite** as the database
- 🎨 Styled with **Bootstrap**
- 🔗 Built with Django framework

## 📂 Project Structure
```
📦 Python-Webshop-Django
 ┣ 📂 products
 ┃ ┣ 📂 templates
 ┃ ┃ ┗ 📜 index.html
 ┃ ┣ 📜 models.py
 ┃ ┣ 📜 views.py
 ┃ ┗ 📜 urls.py
 ┣ 📂 pyshop
 ┃ ┣ 📜 settings.py
 ┃ ┣ 📜 urls.py
 ┃ ┣ 📜 wsgi.py
 ┃ ┗ 📜 asgi.py
 ┣ 📂 templates
 ┃ ┗ 📜 base.html
 ┣ 📜 manage.py
 ┣ 📜 .gitignore
 ┣ 📜 pyshop.jpg
 ┗ 📜 README.md
```

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Pouria-Samadi/Python-Webshop-Django.git
   cd Python-Webshop-Django
   ```

2. **Create a virtual environment (optional but recommended)**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations**
   ```bash
   python manage.py migrate
   ```

5. **Start the Django server**
   ```bash
   python manage.py runserver
   ```

6. **Open in browser**
   ```
   http://127.0.0.1:8000/products/
   ```

## 🌟 Contributing
Feel free to fork the repo and submit a **Pull Request** if you want to add features or fix bugs.

## 📝 License
This project is open-source and free to use.
```
