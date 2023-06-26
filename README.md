# Django Project Web Application
Welcome to the Django Project Web Application! This web application allows you to manage and showcase your bakery products online. With Django Project, you can create, update, and delete bakery items, manage customer orders, and track inventory, all from a user-friendly interface.

## Installation
To install Django Project, please follow these steps:

Make sure you have Python 3 installed on your system. You can download Python from the official website: Python.org.
* Clone the Django Project repository from GitHub:
  * `git clone https://github.com/ashvtosh/Django-Project.git`
* Navigate to the project directory:
  * `cd Django-Project`
* Create a virtual environment to isolate the project's dependencies:
  * `python3 -m venv env`
* Activate the virtual environment:
  * `env\Scripts\activate`
* Set up the database by applying migrations:
  * `python manage.py migrate`
* Create a superuser account for accessing the Django administration portal:
  * `python manage.py createsuperuser`
* Start the development server:
  * `python manage.py runserver`
* Open your web browser and visit http://localhost:8000 to access the Django Project web application.

## Django Administration Portal
The Django Administration Portal provides an interface for managing the backend of the Django Bakery web application.
Here are the steps to access and utilize the Django Administration Portal:

Start the development server by running the following command:
`python manage.py runserver`
* Open your web browser and visit http://localhost:8000/admin.
* Log in using the superuser account you created during the installation process.
* Once logged in, you will have access to various administrative features, including:
  * Bakery Item Management: Add, update, or delete bakery items. You can specify the name, price, description, and other relevant details for each item.
  * Order Management: View and manage customer orders. You can see the details of each order, mark them as fulfilled, and update the status.
  * Inventory Tracking: Keep track of your bakery item inventory. You can view the current stock levels and receive notifications when items run low.
  * User Management: Manage user accounts and permissions. You can create new user accounts, assign roles, and restrict access to certain areas of the application.
  * Settings: Configure various settings for the Django Bakery application, such as email notifications, payment gateway integration, and more.
Feel free to explore the Django Administration Portal and utilize its features to manage your project web application efficiently.

## License
Django Project is released under the MIT License. Feel free to use, modify, and distribute the application according to the terms of the license.
