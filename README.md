# Old-Phone
This project simulates the old Sony phone's keypad (like those used in the K700 model), which maps keypress sequences to text. The program takes a string of keypresses and outputs the decoded message based on how many times each key is pressed.
## Overview
In the past, mobile phones had keypads with multiple letters assigned to each number key (e.g., pressing 2 multiple times would give different letters like "A", "B", or "C"). This project models that behavior and decodes a sequence of keypresses from such a keypad.
## How It Works
* Keypad Mapping: Each digit from 0 to 9 corresponds to a set of characters (e.g., 2 maps to "ABC", 3 maps to "DEF", etc.).
* Input Sequence: The user enters a sequence of keypresses, with each digit possibly being pressed multiple times to select a letter from its corresponding group.
## Special Keys:
* (#) signifies the end of the input and triggers the decoding of the input.
* (*) is used to remove the last character from the output.
* A space ( ) separates words and also processes the sequence before it.
## Features
* Decodes a sequence of keypresses.
* Supports keypress repetitions to select different letters for each digit.
* Handles special characters like * for deletion and # for ending input.
* Alerts the user if invalid characters are entered.
