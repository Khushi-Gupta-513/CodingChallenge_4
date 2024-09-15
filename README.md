# CodingChallenge_4

# Inventory Management System

# Overview

The Inventory Management System is designed to help a small electronics store manage its inventory efficiently. It automates tracking of products, updates stock levels after sales, checks for low inventory, and calculates the total value of remaining stock.

# Features

1. Track Products: 
   - Maintain an inventory of products, including details such as name, price, quantity in stock, and a threshold for low stock levels.

2. Display Product Details: 
   - View detailed information for each product, including its name, price, current quantity, and whether it is "In Stock" or "Low Stock" based on the predefined threshold.

3. Update Stock After Sales: 
   - Adjust the stock quantity for products when sales occur. The system checks if the product's stock has fallen below the low stock level or if it is out of stock and provides appropriate notifications.

4. Check for Low Stock Products: 
   - Identify and list products that have a quantity below their low stock threshold to facilitate timely reordering.

5. Calculate Total Inventory Value: 
   - Compute the total value of all products currently in stock. This helps in understanding the financial worth of the inventory.

6. Process Sales: 
   - Handle sales transactions by reducing the quantity of sold products from the inventory. If the product is not found, an error message is logged.

# Project Setup

1. Initialize Inventory: 
   - The inventory is initialized with a list of product objects. Each product includes attributes such as name, price, quantity, and low stock level.

2. Functionality:
   - Functions are implemented to display product details, update stock levels, check for low stock, calculate inventory value, and process sales.

# Usage

- Displaying Product Details**: Use the provided function to view details of any product, including its stock status.
- Updating Stock: Adjust stock quantities after sales and receive notifications if products fall below low stock levels.
- Checking Low Stock: List products that need restocking based on their current quantities.
- Calculating Inventory Value: Determine the total value of the inventory to assess financial standing.
- Processing Sales: Manage sales transactions and ensure stock levels are updated accordingly.

