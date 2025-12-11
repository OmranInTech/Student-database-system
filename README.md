# Student Database Management System

![Django](https://img.shields.io/badge/Django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

**Student Database Management System** is a web application built using **Django**, **HTML**, and **CSS** to manage student records efficiently. It includes modules for adding, editing, viewing, and deleting student information with a clean and user-friendly interface.

---

## 📂 Project Structure

```
/studenttd
 ├── /admin_app
 │    ├── admin.py
 │    ├── apps.py
 │    ├── forms.py
 │    ├── models.py
 │    ├── tests.py
 │    └── views.py
 ├── /templates
 │    ├── student.html
 │    ├── edit.html
 │    ├── home.html
 │    └── register.html
 ├── settings.py
 └── manage.py
```

**Details:**
- **admin_app**: Handles all backend logic including models, forms, views, and admin configurations.
- **templates**: Contains HTML files for different pages (Home, Register, Edit, Student list).
- **settings.py**: Django project configuration.
- **manage.py**: Django command-line utility.

---

## 🌟 Features

- Add, edit, delete, and view student records.
- User-friendly interface for easy navigation.
- Modular Django app structure for scalability.
- Validations through Django forms.
- Responsive HTML/CSS frontend.

---

## 🚀 Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/studenttd.git
```

2. **Navigate to the project folder:**

```bash
cd studenttd
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

4. **Apply migrations:**

```bash
python manage.py migrate
```

5. **Run the development server:**

```bash
python manage.py runserver
```

6. Open [http://localhost:8000](http://localhost:8000) to view the app.

---

## 📌 Usage

- Navigate to the **Home** page to see student records.
- Use **Register** to add a new student.
- Edit student details using the **Edit** page.
- Delete student records directly from the **Student List** page.

---

## 🛠 Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS
- **Database:** Default Django SQLite (can be changed to MySQL or PostgreSQL)

---

## 📬 Contact

For questions or support:  
**Email:** ahmadzai.omran12@gmail.com
