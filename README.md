# 🚀 Django E-commerce Application
Welcome to my Django E-commerce Application! This project allows users to register, manage products, and place orders. Let's explore its features and how you can set it up.

## 🌟 Features
- **User Registration and Authentication**: Users can sign up, log in, and manage their profiles.
- **Product Management**: Admins can add, update, and delete products.
- **Order Management**: Users can place orders, and admins can manage them.

## 🛠️ Technologies Used

### Backend

- **Django**: Web framework for building the application.
- **SQLite**: Database for storing user and product data.

### Frontend

-**HTML & CSS**: Structure and styling for the web pages.

## 🚀 Getting Started

1. **Clone the Repo**:

<<<<<<< HEAD
    ```bash
=======
'''bash
>>>>>>> 1d3d2b31ffcde3bf669a5e5105d72d495cf39320
    git clone https://github.com/ChanwooBrianKim/Django-project.git
    cd Django-project

2. **Create and Activate Virtual Environment**:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. **Install Dependencies**:

    ```bash
    pip install -r requirements.txt

4. **Apply Migrations**:

    ```bash
    python manage.py migrate

5. **Run the Development Server**:

    ```bash
    python manage.py runserver

6. **Open in Browser**:
    ```bash
    http://127.0.0.1:8000/

## 🤔 How to Use

- **Register and Log In**: Create an account or log in with existing credentials.
- **Manage Products**: Admin users can add, update, or delete products.
- **Place Orders**: Users can browse products and place orders.

## 📂 Project Structure

- **fc_django/**: Main project directory containing settings and configurations.
    - **settings.py**: Configuration for the Django project.
    - **urls.py**: URL routing for the project.
    - **wsgi.py and asgi.py**: Deployment configurations.

- **fcuser/**: User management app for handling registration and authentication.
    - **models.py**: Defines the user model.
    - **views.py**: Contains views for user-related actions.
    - **urls.py**: URL routing for user-related actions.
    - **forms.py**: Forms for user registration and authentication.

- **product/**: App for managing products.
    - **models.py**: Defines the product model.
    - **views.py**: Contains views for product-related actions.
    - **urls.py**: URL routing for product-related actions.
    - **forms.py**: Forms for product management.

- **order/**: App for managing orders.
    - **models.py**: Defines the order model.
    - **views.py**: Contains views for order-related actions.
    - **urls.py**: URL routing for order-related actions.
    - **forms.py**: Forms for order management.

- **templates/**: Directory containing HTML templates.
    - **base.html**: Base template for the application.
    - **home.html**: Home page template.

- **manage.py**: Command-line utility for administrative tasks.
- **db.sqlite3**: SQLite database file.
- **requirements.txt**: List of dependencies for the project.

## 🚀 Future Enhancements
- **User Profiles**: Allow users to update their profiles.
- **Order History**: Display past orders for users.
- **Payment Integration**: Integrate payment gateways for order processing.

## 🙏 Acknowledgements
- **Django**: For the web framework.
- **MDN Web Docs**: For documentation and resources.
