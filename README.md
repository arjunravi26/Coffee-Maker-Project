Coffee Maker Project
Introduction
This Python project models a coffee maker machine that allows users to place orders for various coffee drinks. The system tracks available resources, processes orders, and handles payments. It consists of three main components: CoffeeMaker, Menu, and MoneyMachine.

Components
1. CoffeeMaker (coffee_maker.py)
Class that models the coffee maker machine.
Manages resources such as water, milk, and coffee.
Provides methods for reporting resources, checking resource sufficiency for a drink, and making coffee.
2. Menu (menu.py)
Class that models the menu of available drinks.
Defines a MenuItem class to represent each drink with its ingredients and cost.
Provides methods for retrieving available menu items and finding a specific drink.
3. MoneyMachine (money_machine.py)
Class that models the money processing machine.
Handles the insertion of coins, calculates the total payment, and processes payments.
Keeps track of the machine's profit.
Usage
1. Run main.py
Execute the main script to interact with the coffee maker.
Choose drinks from the menu, view reports, and turn off the machine.
$ python main.py
