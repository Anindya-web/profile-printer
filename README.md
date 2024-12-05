# Profile-printer
## Overview
This Python program is a simple interactive script that prompts the user to input their name, age, and favorite hobby. Once the user provides this information, the program prints it back in a formatted output.

The purpose of this program is to demonstrate basic input/output operations in Python and introduce users to the concept of dynamic input handling through the `input()` function.

## Features
- Asks the user for their name, age, and favorite hobby.
- Reads and processes user input.
- Displays the entered details in a clear, formatted manner.

## Requirements
- Python 3.x

## How to Run
1. **Ensure Python is Installed**:
   - Check if Python is installed by running `python --version` or `python3 --version` in your terminal or command prompt.
   - If not installed, download and install Python from [python.org](https://www.python.org/).

2. **Run the Script**:
   - Save the program as a `.py` file (e.g., `user_info.py`).
   - Open a terminal or command prompt and navigate to the directory where the script is saved.
   - Execute the script using the command:
     ```bash
     python user_info.py
     ```

3. **Follow the Prompts**:
   - The program will prompt you to enter your name, age, and favorite hobby one by one.
   - After entering each piece of information, press `Enter` to proceed.

4. **View the Output**:
   - The program will display your entered name, age, and favorite hobby in the following format:
     ```
     The name is: [Your Name]
     The age is: [Your Age]
     The favorite hobby is: [Your Hobby]
     ```

## Example
Here is an example of what the program might look like when running:

```
Please, Enter your name: John Doe
Please, Enter your age: 25
Please, Enter your favorite hobby name: Talking with favorite person

The name is: John Doe
The age is: 25
The favorite hobby is: Talking with favorite person
```

## Key Concepts Demonstrated
- **Input Handling**: Using `input()` to take user input.
- **Type Conversion**: Converting input strings to integers using `int()`.
- **String Formatting**: Using f-strings to format and display output.

## Notes
- Ensure that the age input is a valid integer; otherwise, the program will raise a `ValueError`.
- This program is a simple demonstration and can be expanded for more advanced functionalities if needed.



