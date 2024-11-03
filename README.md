# RandompwdGen

Random Password Generator 🔐

This is a Python-based password generator script that creates a secure, randomized password using a combination of letters, digits, and punctuation symbols. This tool is perfect for generating strong, hard-to-guess passwords.

📋 How It Works

The script defines a password length (pass_len) of 8 characters, which you can modify to generate longer or shorter passwords.
It creates a pool of characters (charValues) by combining uppercase and lowercase letters, digits, and punctuation.
List comprehension is used to generate the password by selecting random characters from charValues:

The expression [random.choice(charValues) for i in range(pass_len)] iterates pass_len times, each time picking a random character from charValues.
These characters are then joined together to form a single password string.
The generated password is printed to the screen.

🔍 What is List Comprehension?

List comprehension is a concise way to create lists in Python. Here, it helps generate the password in a single line by:

-Iterating a specific number of times (pass_len).

-Selecting random characters from the character pool (charValues).

-Building a list of these characters, which is then joined into a final password string.

This approach is efficient and keeps the code compact.
