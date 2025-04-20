# Shopping Website Project

## Project Description
This is a simple e-commerce shopping website built using PHP, MySQL (MariaDB), and Bootstrap for styling. The project allows users to sign up, log in, browse products, add products to their cart, and place orders.

## Features
- User registration and login system
- Product listing with images, prices, and details
- Shopping cart functionality to add and remove products
- Order placement and order tracking
- Responsive design using Bootstrap

## Technologies Used
- PHP 8.x
- MySQL / MariaDB
- HTML, CSS, Bootstrap 5
- JavaScript (basic validation)

## Installation and Setup
1. Clone or download the project files to your local server directory (e.g., XAMPP `htdocs` folder).
2. Import the database schema:
   - Use phpMyAdmin or MySQL CLI to import the `ecommerce_shopping_1.sql` file into your MySQL/MariaDB server.
3. Configure database connection:
   - Update the database connection settings in `shared/connection.php` if necessary (host, username, password, database name).
4. Start your local server (e.g., Apache in XAMPP).
5. Access the website via `http://localhost/Project-8-Shopping Website/index.php` or directly `http://localhost/Project-8-Shopping Website/shared/login.html`.

## Usage
- Register a new user via the signup page.
- Log in with your credentials.
- Browse products on the home page.
- Add products to your cart.
- View your cart and place orders.
- Track your orders.

## Folder Structure
- `customer/` - Contains customer-related PHP files for cart, orders, authentication, and product browsing.
- `shared/` - Contains shared resources like login, signup pages, CSS, images, and database connection.
- `ecommerce_shopping_1.sql` - Database schema and initial data.

## Database Tables
- `user` - Stores user credentials and roles.
- `product` - Stores product details including name, price, description, and image path.
- `cart` - Stores products added to users' shopping carts.
- `placeorder` - Stores placed orders.

## Author
Project created for educational purposes.

## License
This project is open source and free to use.
