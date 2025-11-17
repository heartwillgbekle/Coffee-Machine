# Coffee-Machine

A simple object-oriented coffee machine simulator written in Python. The program lets you order drinks from a menu, checks whether there are enough resources, processes your payment, and then updates the machine’s internal inventory.

## Features

- Command-line menu to order drinks (e.g., espresso, latte, cappuccino)
- Tracks available resources (water, milk, coffee, money)
- Handles coin/payment input and calculates change
- Prints a report of current resources and profit
- Allows turning the machine off via a command

## Project Structure

- `main.py` – Main entry point; runs the coffee machine loop
- `coffee_maker.py` – Handles making drinks and managing resources
- `menu.py` – Defines the menu and available drinks
- `money_machine.py` – Manages payments and tracks profit
- `main1.py` – Alternate/experimental version of the main program (if used)

## Requirements

- Python 3.x

No external libraries are required.

## How to Run

```bash
git clone https://github.com/heartwillgbekle/Coffee-Machine.git
cd Coffee-Machine
python main.py
