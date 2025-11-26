# Food Ordering System

A simple **Food / Item Ordering and Management System** built using **PHP**, **MySQL**, **HTML**, **CSS**, and **JavaScript**.  
This project allows users to browse a menu, place orders, and allows admins to manage orders.

---

## Table of Contents

- [Description](#description)  
- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Limitations](#limitations)  
- [License](#license)  

---

## Description

This project is a web-based food ordering system designed to simulate the process of ordering food online.  
It includes functionalities for both **users** and **admins**, including:  

- User registration and login  
- Viewing available food items  
- Placing orders  
- Admin management of orders  

The system uses a **MySQL database** to store user, menu, and order information.  

> **Note:** This project is intended for learning and demonstration purposes. It is **not production-ready**.

---

## Features

- User Registration and Login  
- Browse Food Items / Menu  
- Place Orders (with fake payment system)  
- Admin Panel to view all orders  
- Basic Dashboard for order management  

---

## Technologies Used

- PHP  
- MySQL  
- HTML / CSS / JavaScript  
- Apache / XAMPP or any PHP server  



How To Install -
---------

1. Create Database food.
2. Run food.sql script provided in sql folder.
3. Go to login.php and try out our application. Sample user credentials can be found in users & wallet_details table.

Note -
---------
1. This is not ready for PRODUCTION.
2. The username and password of sample users are stored in table `users`.
3. Only Customers with "Verified" status can place orders using "Cash on Delivery" option.
4. By default a new customer gets 2000 coins in Wallet on signing up, and a fake Credit card number & CVV number is generated and stored in SQL Table "wallet_details" with corresponding new customer's ID.
5. Use that Card Number & CVV while placing an order, else order won't be successful or use "Cash on delivery" option.
6. What's lacking? Dynamic payment(real payment system) and error reporting lacks in this project. And also one might wish for showing corresponding food item's photo and all that stuff.
