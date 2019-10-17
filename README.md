# Bamazon
A mock storefront with departments and products. Customers, managers, and supervisors are able to use this app.

# Motivation
A Node app for customers to view items and place orders, for managers to perform inventory control and add new products, and for supervisors to track department profitability and add new departments.

# Technology used

. Node.js
. Javascript
. MySQL
. inquirer
. console.table

# Getting Started
Clone the repository.
Run command npm install in Terminal.
Set up MySQL database. If you do not already have MySQL installed, you can visit the installation page to install the correct version of MySQL for your machine. Once you have installed MySQL, create the Bamazon database used the SQL code in Bamazon.sql.
Choose an interface below.

# BamazonCustomer
The customer interface takes in orders from customers. If inventory is available, it will calculate the total cost for the customer and delete the stock from the store's inventory. If inventory is not available, the app will alert the customer.

![image](https://user-images.githubusercontent.com/52688618/66983099-9fd23b00-f06c-11e9-9cf1-c6dd8349104d.png)

To use the customer interface, simply type node bamazonCustomer.js in Terminal.

# Bamazon Manager
The manager interface allows the user to:

View Products for Sale
![image](https://user-images.githubusercontent.com/52688618/66983249-fb9cc400-f06c-11e9-9947-c449d838286b.png)


View Low Inventory (Shows all products with a quantity less than 5)
![image](https://user-images.githubusercontent.com/52688618/66983327-29820880-f06d-11e9-9799-5727263ccb57.png)


Add to Inventory (Takes current inventory and updates quantity)
![image](https://user-images.githubusercontent.com/52688618/66983430-74038500-f06d-11e9-9680-b585b566b267.png)


Add New Product (Create and a new entry to the mySQL database)
![image](https://user-images.githubusercontent.com/52688618/66983555-a7461400-f06d-11e9-90e3-a3137dcfe0ff.png)

To use the manager interface, simply type node bamazonManager.js in Terminal.

# Bamazon Supervisor
Still working on it. I have some bug.


