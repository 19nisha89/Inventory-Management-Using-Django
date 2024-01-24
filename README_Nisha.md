
# Inventory Management System

This project is an Inventory Management System built using Django. It allows Inventory Managers to register, create, read, update, and delete products in the inventory.


## Features

- First-name, last-name, and login registration for Other Users and Inventory Manager.
- CRUD operations for products.
- Dashboard created with HTML.
- Product attributes: product Id, name, description, stock quantity, price, user, modified user, User ID.
- Automatic creation of a user ID upon registration.
- Consistent view of products in the latest state.
- History of the product’s modifications with latest version and its modified states.


## Installation

Creating a virtualenv for the project

```bash
  pipenv shell
```
Install Django

```bash
  pipenv install django
```
Install dependency,
If it's not installed or getting error then install it
```bash
  pip install crispy-bootstrap5
```
Create Project

```bash
  django-admin startproject inventory_management
```
Create app
Go to the directory where manage.py is given

```bash
  django-admin startapp inventory
```
Apply Migrations

```bash
  python manage.py makemigrations
  python manage.py migrate
```
Create Super User/Admin

```bash
  python manage.py createsuperuser
```
Run the server

```bash
  python manage.py runserver
```
And navigate to http://127.0.0.1:8000/

To go to admin page navigate to http://127.0.0.1:8000/admin/

## Usage

- **Sign In**:
  - Log in as a user or administrator to access the system.

- **Product Management**:
  - You have the ability to Create, Edit, or Delete products:
    - Navigate to the respective product management section to perform these actions.

- **Audit History**:
  - Click on the "Track" button to view the audit history of a specific product.

- **View All Products (Admin/Inventory Manager)**:
  - If you have admin or Inventory Manager privileges, you can see a comprehensive list of all products.




## Authors

- Nisha Makwana

