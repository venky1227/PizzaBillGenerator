Pizza Ordering System
This project implements a simple pizza ordering system in Java. It consists of two classes: Pizza and DeluxPizza.

Pizza Class
The Pizza class represents a basic pizza with options to add extra cheese, extra toppings, and opt for take-away. It calculates the total bill based on the selected options.

Features:
Initialize a pizza with options for vegetarian or non-vegetarian.
Add extra cheese to the pizza.
Add extra toppings to the pizza.
Opt for take-away, which adds a backpack fee to the bill.
Generate a bill with itemized details of selected options and the total amount.
DeluxPizza Class
The DeluxPizza class extends the Pizza class and represents a deluxe pizza. It automatically adds extra cheese and extra toppings to the pizza.

Features:
Automatically adds extra cheese and extra toppings to the pizza.
Inherits all features from the Pizza class.

Usage
To use the pizza ordering system, create instances of the Pizza or DeluxPizza class and call the appropriate methods to customize the pizza and generate the bill.

java
// Example usage of Pizza class
Pizza basePizza = new Pizza(true);
basePizza.addExtraCheese();
basePizza.addExtraToppings();
basePizza.takeAway();
basePizza.getBill();

// Example usage of DeluxPizza class
DeluxPizza dp = new DeluxPizza(false);
dp.takeAway();
dp.getBill();
