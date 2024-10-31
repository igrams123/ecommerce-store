Trendy Sneakers - Django E-commerce Project
Welcome to the Trendy Sneakers project! This project is a comprehensive Django-based e-commerce application built to manage and sell sneakers. It provides a full-featured shopping experience, including user authentication, cart management, payment integration, and a user-friendly interface.

Table of Contents
Features
Installation
Configuration
Usage
Testing
Contributing
License
Features
User Authentication: Users can register, log in, and reset passwords.
Product Management: Admins can add, edit, and delete sneakers.
Search and Filter: Users can search for sneakers by name or category.
Cart and Checkout: Add items to the cart, adjust quantities, and proceed to checkout.
Payment Integration: M-Pesa payment processing using STK Push.
Save for Later: Users can save sneakers to view them later.
Responsive Design: Works on both desktop and mobile devices.
Installation
To get started with the Trendy Sneakers project, clone the repository and install the dependencies.

Prerequisites
Python 3.x
Django 3.x or higher
pip (Python package installer)
Steps
Clone the repository:

bash
Copy code
git clone https://github.com/igrams123/trendy-sneakers.git
cd trendy-sneakers
Create a virtual environment:

bash
Copy code
python3 -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run migrations:

bash
Copy code
python manage.py migrate
Create a superuser for accessing the admin interface:

bash
Copy code
python manage.py createsuperuser
Run the development server:

bash
Copy code
python manage.py runserver
Visit http://127.0.0.1:8000 in your browser to start using the application.

Configuration
In your settings.py file, you’ll need to configure your database, email settings (for password reset), and M-Pesa API credentials. Refer to the .env.example file for environment variables.

M-Pesa Integration
Make sure to add your M-Pesa API keys in your environment variables. The integration is configured for a sandbox environment by default.

Usage
Navigate to the homepage: Browse available sneakers.
User Account: Register or log in to add items to your cart and save for later.
Search: Use the search bar to find specific sneakers by name.
Cart and Checkout: View your cart, adjust quantities, and proceed to checkout.
Payment: Enter your phone number to receive an M-Pesa STK push for payment.
Testing
To run the tests for the project, use:

bash
Copy code
python manage.py test
Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch for your feature or bug fix:
bash
Copy code
git checkout -b feature-name
Commit your changes and push to your fork.
Create a pull request describing your changes.
License
This project is licensed under the MIT License. See the LICENSE file for more information.

Thank you for checking out Trendy Sneakers!
