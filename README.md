# DiceApp

Simple TUI (text-based user interface) application for dice rolling simulations. Generates an ASCII diagram of the dice faces. Based on source code from [this Real Python tutorial](https://realpython.com/python-dice-roll/).

## How It Works

The program prompts the user to enter a number of dice to roll between 1 and 6. DiceApp then validates the input as an integer between 1 and 6. If the input cannot be validated, DiceApp tells the user to enter a valid number and exits the program.

If the input is valid, the program rolls the appropriate number of dice and returns an ASCII representation of each die.