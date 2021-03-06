# bamazon

### Overview

#### An Amazon-like storefront built to run on Node.js with persistent data storage using MySQL.  

1. Customer Mode: app takes orders from customers and depletes stock from the store's inventory.
2. Manager Mode: app allows the manager to 
    1. View Products for Sale
    2. View Low Inventory
    3. Add to Inventory
    4. Add New Products



### Requirements: 
1. Node.js
2. MySQL

### Getting Started
1. Clone Git repository to your local machine
2. In the main directory run ```$ npm install```
3. After installing MySQL:
    1. Run the bamazon.sql script the create the database schema
    2. Run the seeds.sql script to populate the database with products

### Functionality

1. Customer Mode
    1. From the command line, navigate to the bamazon directory and execute bamazonCustomer.js

    ```$ node bamazonCustomer.js```

    2. Follow the prompts to shop for items and place orders
    <img src="screenshots/bamazon_customer.gif?raw=true" alt="Customer Order" width="600px" />
2. Manager Mode
    1. From the command line, navigate to the bamazon directory and execute bamazonCustomer.js

    ```$ node bamazonManager.js```

    2. Follow the prompts to view products, manage inventory or add new products
    <img src="screenshots/bamazon_customer.gif?raw=true" alt="Customer Order" width="600px" />

