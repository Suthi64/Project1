# DIY Tea & Juice Maker 🧋

## Overview

DIY Tea & Juice Maker is a Python program that allows users to customize their own cold beverage by selecting different ingredients and preferences. The program calculates the required amount of ice cubes needed to reach the user's desired drink temperature.

---

## Features

- Choose between a milk-based or fruit-based beverage
- Customize milk options based on lactose intolerance
- Select tea type:
  - Black Tea
  - Green Tea
  - Matcha
  - No Tea
- Add toppings:
  - Bobas
  - Coconut Jelly
  - No Topping
- Choose drink size:
  - Small
  - Medium
  - Large
- Select desired temperature
- Calculate the number of ice cubes required to cool the beverage
- Validate user inputs and handle invalid selections

---

## Technologies Used

- **Programming Language:** Python
- **Concepts Implemented:**
  - User input handling
  - Conditional statements
  - Variables and data types
  - Mathematical calculations
  - Input validation

---

## How It Works

The program guides the user through a series of choices to customize their beverage.

The user selects:
1. Beverage base (milk or fruit)
2. Tea type
3. Toppings
4. Cup size
5. Desired temperature

Based on the selected cup size and temperature, the program calculates the amount of ice needed to cool the drink from room temperature to the desired temperature.

---

## Temperature Calculation

The program uses heat transfer calculations to determine the number of ice cubes required.

Assumptions:
- Initial beverage temperature: 25°C
- Ice melting temperature: 0°C
- 1 mL of beverage = 1 g
- Each ice cube has a mass of 5g

---

## Example Output

```
Welcome to the DIY Tea & Juice Maker!

Your drink is a mango juice and Green Tea with Bobas.
The temperature of your beverage will be 3.0 Celsius degree after all 20 ice cubes melted.

Have a nice day!
```
