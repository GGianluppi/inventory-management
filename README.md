# CS50 Final Project - Inventory Management System

Inventory management system was created to improve the operation of my business. The main idea of this project is to create an inventory system for my business to manage products. This project has a login screen, products and inventory session where the admin can manage, adding or removing new products. The project will be improved with new functions.

# Technologies used:

 * Python
 * Django
 * HTML
 * CSS
 * JavaScript
 * jQuery
 * Ajax
 * Bootstrap 5.


# How the webpage works?

It has a simple and pleasant user interface using Bootstrap 5. The project also has user-friendly features and functionalities. The system can be accessed by users which are the admin and staff. After acces the website you can enter these fields:

   * Login
   * Sign up

In the session product you can add product:

   * Product code
   * Product name
   * Price
   * Status (Available / Not available)
   * Description

The admin has the privilege to access Django's admin panel/site and manage the list of users.

The staff users are only allowed to manage the site. Futhermore, the users can add stocks to each product and the system automatically calculate the available stocks per product.


# Project structure:

**Login and Registration Page**

User can log in or create a new account.

<p align="center">
<img src="https://user-images.githubusercontent.com/104764600/219991044-085fbaec-301c-4887-a08e-f2459de78fda.png" width="850" height="400">
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/104764600/219991403-afdd1c79-b641-47ec-ad9c-23026a3a035a.png" width="850" height="400">
</p>

**Home page**

This page is empty, only with my business logo

<p align="center">
<img src="https://user-images.githubusercontent.com/104764600/219991367-fde26f41-96d9-45f3-be87-8814b13d4fb6.png" width="850" height="450">
</p>


**Product**

In this session the admin and staff can change, add, edit or remove products.

   * Add New Product
   * List All Products
   * Edit Product
   * Delete Product

<p align="center">
<img src="https://user-images.githubusercontent.com/104764600/219991337-2cc29e07-1282-4f87-af68-cede6f968bb2.png" width="850" height="450">
</p>

   
**Inventory**

The user can view the quantity of product in stock, as well as view the history of the product, adding or editing.

   * List All Products
   * View Products Stock History
   * Add New Product Stock
   * Edit Product Stock
   * Delete Product Stock

<p align="center">
<img src="https://user-images.githubusercontent.com/104764600/219991295-d51daaa6-d151-4906-b51d-8cf7baba3e78.png" width="850" height="450">
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/104764600/219994532-cacff7ff-03cc-4064-b55e-6cbf8eb39b1f.png" width="850" height="450">
</p>



**My account**

In this session the user has the main account information. The user can update account, update password and logout.

   * Update account
   * Update password
   * Logout
   
<p align="center">
<img src="https://user-images.githubusercontent.com/104764600/219992009-c6c3691a-80b5-47c3-a1a8-b20fc49b8358.png" width="850" height="450">
</p>


# Possible improvements:

As all applications this one can also be improved. Possible improvements:

* In the home page session, information of each registered user. In addition, total values of the products
* Sales Transaction Form with possibility to save in PDF
* Invoice List
* Notificaitons to email about new products or any changes


# How to launch application:

**1. Clone Project**

`git clone https://github.com/GGianluppi/inventory-management.git`

**2. Go To Project Directory**

`cd Inventory`

**3. Create Virtual Environment**

`python3 -m venv venv`

**4. Active Virtual Environment**

`source venv/bin/activate`

**5. Install Requirements File**

`pip install -r requirements.txt`

**6. Migrate Database**

`python manage.py migrate`

**7. Create Super User**

`python manage.py createsuperuser`

**8. Run Project**

`python3 manage.py runserver`
   
**9. You are ready to go!**

`Open a web browser and browse http://localhost:8000/ or http://127.0.0.1:8000/`
