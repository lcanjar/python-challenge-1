# menu.py program for Python-Challenge-1

# What does this program do?
This program creates an order entry system for a food truck.  Through a series of prompts, it gets (and validtes) the menu option(s) selected, the quantity of each menu item ordered, and produces a tabular list summarizing the items ordered and the total cost.

# How to use the program?
Instantiate the program by running the menu.py program.  This can be done in and IDE or BASH prompt.

# Code overview:
1. Initialize the menu (menu dictionary object)
2. Create an order list to store customer menu selections (list of dictionaries).  One dictionary for each item ordered--to include item name, price, and quantity.
3. While True, print the menu and prompt customer to enter menu category.
4. Prompt customer to enter menu selection (item #) and validate entry.
5. Ask customer to enter quanity for the menu selction and validate entry.
6. Create order object and pass item name, price, and quantity.  Append this order object to the order_list to keep a running tally of ordered items.
7. Prompt the customer if they want to order another item.  Validate entry.  Then break and start back at the beginning of the place order loop.  (#3 through 6, above)
8. Loop through the order_list and print out the items ordered along with a total for the order.

# Output
1. Menu categories
2. Sub menu items
3. List of items ordered, along with total
4. Various check prompts to ensure customer entries are valid

# Modifed by Lou Canjar for UNC bootcamp
© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
