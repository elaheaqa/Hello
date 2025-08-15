# Hello
Here we go to Goals
# main.py
# A simple GitHub-friendly Python project
# Author: Your Name

from datetime import datetime
import random

quotes = [
    "Code is like humor. When you have to explain it, it’s bad.",
    "First, solve the problem. Then, write the code.",
    "Experience is the name everyone gives to their mistakes.",
    "In order to be irreplaceable, one must always be different.",
    "Java is to JavaScript what car is to Carpet."
]

def show_welcome():
    print("Welcome to My GitHub Project!")
    print(f"Today is: {datetime.now().strftime('%Y-%m-%d %H:%M:%S')}")
    print("Here's your random programming quote:\n")
    print(random.choice(quotes))

if __name__ == "__main__":
    show_welcome()
