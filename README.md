# OnlineGrocerySystem
WDL mini project

This project is implemented as a project under the scopr of web development and online food chains currently popular in markets.
The implementation of this is done using:
1. Django web framework
2. Django Rest framework to make REST API
3. Tokenauthentication for securing API, currently disabled
4. Python programming language
5. frontend in HTML, CSS, JavaScript and bridge it with Jinja templating
6. Database in Sqlite



This project implements an Online Grocery selling and buying process. Using this a user can either buy groceries or sell them by listing as vendors.
It contains separate login processes for customers and vendors. Vendors have to submit their profile in the website and wait for a confirmation from the 
admins to approve it.
After approval the vendor can create a list or board of what items are available for sale, with their quantities and cost accordingly. They can manage the 
remaining stock of goods and digital invoice of what has been sold so far and to whome.
The customers can select the quantity of desired item to buy and place an order with 1 or more vendors. The information like customer name, delivery address, 
contact number is given to the vendor with the order as well. By default every order is given a status of placed, which is monitored by the vendor and can change
the order status accordingly. This change in order status is reflected in the customers' order history list as well.

The customer also has a digital copy of orders with details and history.
