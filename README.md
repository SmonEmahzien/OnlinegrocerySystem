This project is a web-based application for managing a grocery store's inventory, designed to provide a simple and user-friendly interface for managing products, viewing and editing inventory, and handling database operations.
Frontend
HTML/CSS: Used to build the structure and style of the web pages.
JavaScript: Provides interactivity and dynamic features for a responsive user interface.
Bootstrap: Ensures responsive design and easy-to-use components such as forms, modals, and navigation bars.
Backend
Python: The core language used to handle business logic and manage backend operations.
Flask: A lightweight web framework used for handling routes and server-side logic.
Database
MySQL: Used for storing product data, inventory, and related records. The database manages CRUD operations for the grocery store management.
Features
Add Product: Easily add new products to the inventory using the UI or API.
View Products: Display a list of products with details like name, unit, and price.
Delete Product: Remove products from the database.
Update Product: Modify product details directly from the interface.
Database
The MySQL database contains the following tables:

products: Stores product information such as name, unit of measure (UOM), and price per unit (PPU).
uom: Stores units of measure for products, such as "kg", "liters", etc.
API Endpoints
GET /getproducts: Retrieve all products from the database.
POST /addproduct: Add a new product to the inventory.
DELETE /deleteproduct/<id>: Remove a product by its ID.
