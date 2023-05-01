# E-commerce Project

#### This is an E-commerce Application for a Furniture Store developed using Mongo DB, Express JS, Angular JS and Node JS (MEAN Stack).

### Title: Online Furniture Store

### Website Name: The Furniture Mart

### Description:

The project is “The Furniture Mart” web application which provides a platform for buying and selling of furniture like Bookshelf, Mattress and Bed etc.

### Assumptions: Admin account is pre-created.

The following functionalities are supported:

1. Register Signup – Register new user to system. As a part of registration we check if:
   i) the username and email is already registered to the system
   ii) the form is valid
   iii) the password is strong enough. Hashed versions of passwords are stored in the database.
2. User login – Registered user can login

3. Available products will be listed. User can filter out the results based on category and can also search for a specific product. Search and filtering are integrated.
4. Paging functionality is incorporated with filtering, search and listing products functions.

5. After logging in, the user can add products to the cart and checkout. Pricing is included. Once the product is checked out inventory will be updated. The user can track orders.
6. The user can remove the product or update their quantity in the cart.

7. User can see the history of purchases.
8. There is also a provision for ratings and review for the products bought by the users.

9. The admin user can add new items, list all products, update and delete (soft delete) items. While adding/updating items, the admin can upload/update images.

### Database Design:

We used MongoDB for database implementation and hosted data on Atlas cluster.
Technologies:
Front-end: HTML, CSS, Bootstrap, AngularJS, AJAX, JQuery Back-end: NodeJS, ExpressJS, MongoDB, MongoDB Atlas Service

> Note: Please enter credentials in seller.js and config.js for code to work properly.
