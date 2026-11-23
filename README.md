# nextbyte-python-internship-week-2
# HomeSaver Hub – Smart Household Problem Solver

## About the Project
HomeSaver Hub is a Python-based application designed to solve common household problems. It provides simple solutions for managing grocery expenses, estimating electricity bills, checking food expiry dates, calculating water supply, and organizing household chores.

The project uses Python functions, loops, conditional statements, and input validation. It also includes a simple interactive GUI built using **ipywidgets** in Google Colab.

## Features

The application includes five modules:

1. **Grocery Budget Planner**
   - Takes the monthly grocery budget.
   - Calculates the total cost of grocery items.
   - Displays the remaining budget or warns if the budget is exceeded.

2. **Electricity Bill Estimator**
   - Takes appliance wattage and daily usage hours.
   - Calculates monthly electricity consumption in units (kWh).
   - Estimates the monthly electricity cost.

3. **Pantry Expiry Manager**
   - Takes food names and expiry dates.
   - Checks how many days are left before expiry.
   - Identifies expired items and items that should be used soon.

4. **Water Tank Calculator**
   - Takes tank capacity, current water level, and daily water usage.
   - Estimates how many days the remaining water will last.
   - Displays a warning when the water level is low.

5. **Household Chore Planner**
   - Takes household tasks and their completion status.
   - Tracks completed and pending chores.
   - Displays a summary of household tasks.

## Technologies Used
- Python
- Google Colab
- ipywidgets
- datetime module

## Python Concepts Used
- Variables and data types
- Functions
- For loops
- Conditional statements (if-else)
- Lists
- User input
- Input validation
- Exception handling (try-except)

## How to Run the Project

1. Download or clone this repository.
2. Open the `.ipynb` notebook in Google Colab.
3. Run the notebook cells in order.
4. Select a household problem from the dropdown menu.
5. Enter the required information.
6. Click the **Solve Problem** button to view the results.

## Sample Test Cases

| Module | Sample Input | Expected Output |
|---|---|---|
| Grocery Planner | Budget: 5000, Price: 200, Quantity: 2 | Total: 400 PKR |
| Electricity Estimator | 80W, 10 hours/day, Rate: 50 | 24 units, 1200 PKR |
| Pantry Manager | Milk, expiry date yesterday | Expired |
| Water Calculator | Capacity: 1000L, Current: 600L, Usage: 150L/day | 4 days |
| Chore Planner | 2 completed, 1 pending | 2 completed, 1 pending |

## Purpose
The purpose of this project is to apply basic Python programming concepts to real-life household situations and develop problem-solving skills through practical exercises.




---

**Project:** HomeSaver Hub – Smart Household Problem Solver  
**Language:** Python  
**Platform:** Google Colab
