
# Employee Management System

The **Employee Management System** is a Django-based web application that allows users to manage employees within a company. It provides a user-friendly interface to add, edit, delete, and filter employees. It also includes secure user authentication and role-based access control.

## 🔧 Features

- **Employee Management**: Add, edit, and delete employee records (name, position, department, contact info).
- **Filtering/Search**: Easily filter or search employees by name, department, or position.
- **Authentication**: Secure login and registration for users.
- **User Roles**: Admins can manage all data, while regular users may have limited access.
- **Profile Management**: Users can view and update their personal profile information.
- **Responsive UI**: Optimized for desktops, tablets, and mobile devices using Bootstrap.

---

## 🚀 Installation

Follow the steps below to set up the project locally:

1. **Clone the Repository:**

git clone https://github.com/rushijadhavpatil/EMS-Django.git

2. **Navigate into the project directory:**

cd EMS-Django


3. **Create a virtual environment (optional but recommended):**

python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

4. **Install the required dependencies:**

pip install -r requirements.txt

5. **Apply migrations to set up the database:**

python manage.py migrate

6. **Create a superuser for admin access:**

python manage.py createsuperuser

7. **Run the development server:**

python manage.py runserver

8. **Open in Browser:**

Visit [http://localhost:8000](http://localhost:8000)

---

## ⚙️ Configuration

You can configure the project by modifying the `settings.py` file inside the main Django app directory.

### Key Configuration Options:

* **Database**: By default, it uses SQLite. For PostgreSQL/MySQL, update the `DATABASES` section.
* **Static Files**: Served from the `static/` directory. Configure `STATIC_URL` and `STATIC_ROOT` if needed.
* **Media Files**: Uploads such as profile pictures are stored in the `media/` directory. Adjust `MEDIA_URL` and `MEDIA_ROOT` accordingly.

---

## 👥 Usage

1. **Home Page**: Visit [http://localhost:8000](http://localhost:8000)
2. **Register/Login**: Create an account or log in.
3. **Manage Employees**: Add, edit, delete, or search employees via the dashboard.
4. **Admin Panel**: Go to [http://localhost:8000/admin](http://localhost:8000/admin) using your superuser credentials to manage users, roles, and permissions.

---

## 👨‍💻 Contributing

We welcome contributions! Follow these steps to contribute:

1. **Fork the repository**
2. **Create a new branch**:

git checkout -b feature/your-feature-name

3. **Commit your changes**:

git commit -m "Your detailed explanation of your changes."

4. **Push to GitHub**:

git push origin feature/your-feature-name

5. **Open a Pull Request** with a detailed description.


## 🙏 Acknowledgments

This project uses the following open-source tools and libraries:

* [Django](https://www.djangoproject.com/)
* [Bootstrap](https://getbootstrap.com/)
* [Font Awesome](https://fontawesome.com/)
* [jQuery](https://jquery.com/)

---

## 📫 Contact

If you have any questions, suggestions, or feedback, feel free to contact:

* **Name**: Rushikesh Jadhav Patil
* **GitHub**: [rushijadhavpatil](https://github.com/rushijadhavpatil)
* **Email**: rvj96kpatil@gmail.com

---

Thank you for using the **Employee Management System**! We hope it makes your employee management process easier and more efficient.
