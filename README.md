# Restaurant_App
This Java program, Restaurant_App, is a console-based application designed to manage orders in a restaurant. It provides functionality for both new and returning customers to select items from a menu, calculates the bill, and applies discounts for returning customers.
Features
Interactive Menu:

Displays a list of available food items along with their codes.
Users can select items by entering the product codes.
New Customer Handling:

Assigns a unique customer ID to each new customer.
Calculates the total price and VAT for selected items.
Displays the final bill.
Returning Customer Handling:

Validates the customer ID.
Applies a 5% discount to the total bill for returning customers.
Displays the final bill after the discount.
Code-based Item Selection:

Each product has a unique code for easy selection.
Allows customers to add items to their cart by entering product codes.
Dynamic Billing:

Calculates the total price and VAT for items.
Provides an option to calculate the total at any time by entering a specific command (t).
Reusable Code:

Inheritance is used to manage shared functionalities.
Separate classes (newc, oldc, and inheritance) organize logic for new customers, old customers, and shared methods.
Class Descriptions
1. Restaurant_App
The main class that serves as the entry point of the application.
Contains the full() method to display the main menu and handle user choices.
2. inheritance
Provides shared functionalities like displaying the product menu (product() method).
3. newc
Handles the logic for new customers.
Assigns unique customer IDs and calculates the bill based on selected items.
4. oldc
Handles the logic for returning customers.
Verifies customer IDs and applies a 5% discount on the total bill.
Product Menu
Product Name	Product Code
Daryabadi Biryani	DB11
Beef	BF11
Vegetable Biryani	VG11
Burger	BU11
Mutton Rezala	MR11
Fish Tikka	FT11
Mutton Fry	MV11
Chicken Biryani	CB11
Cold Drinks	CD11
How to Use
Clone the repository to your local machine.
Compile and run the program using a Java compiler.
Follow the interactive prompts to place an order.
Choose between a new or returning customer.
Enter product codes to add items to your cart.
For returning customers, enter your Customer ID to receive a discount.
View the final bill and VAT breakdown.
Example Walkthrough
Launch the application.
Select New Customer or Old Customer.
Enter the product codes of items you wish to purchase.
Enter t to calculate the total bill.
View the final bill, including VAT and discounts (if applicable).
