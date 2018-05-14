# iPortables
A servlet-based web application prototype for online retailer of smart portable devices

The following is the high-level description for iPortables website:

    * The store has a StoreManager, Customers, and Salesmen users
    * Each retailer can sell different types of products(Smart Watches, Speakers, Headphones, Phones, Laptops, External Storage)
    * The StoreManager can Add/Delete/Update products
    * Salesman can create Customer accounts and can Add/Delete/Update customer's orders
    * Every product might have accessories that could be bought separately.
    * When a product is selected for a view, all accessories associated with that product must be displayed below the product horizontally.
    * Retailer offers warranty that can be purchased by the customer for every console
    * The customer must be able to create an account online
    * The customer must be able to place an order online, check the status of the order, or cancel the order.
    * The customer will pay using a credit card
    * Some of the products may have retailer special-discounts
    * Some of the products may have manufacturer rebates
    * Customer shall be able to shop online to buy one or multiple items in the same session from the SmartPortables online retailer.
    * In the same session, the customer must be able to add or remove
    items from the shopping cart
    * When the customer chooses to check out:
        1. The customer will enter personal information (Name, Address, Credit Card, etc.)
        2. The customer will be provided with a confirmation number and a delivery date (2 weeks after the order date) that the customer can use to cancel an order at a later timer, though it must be 5 business days before the delivery date.
    * All accounts login information must be stored in SQL database (MySQL)
    * All Customers transactions/orders must be stored in SQL database (MySQL)
    * All order updates to insert/delete/update orders must be reflected in the MySQL database;
    * Customer must be able to submit product reviews
    * Product reviews must be stored in NoSQL database (MongoDB)
    * Add Trending & Data Analytics feature (detailed below)
        1. Top five most liked products
        2. Top five zip-codes where maximum number of products sold
        3. Top five most sold products regardless of the rating
    * StoreManager should be able to view inventory statistics
    * StoreManager should be able to get Sales Report
    * Customer must be able to search for any product and it should include auto completion feature to assist user in search
    * Use Python script to fetch Twitter data deals matching the current product on other website and display it

Source privately hosted at https://bitbucket.org/sashankbv/i-portables
