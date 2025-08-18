# Hello
Here we go to Goals
# main.py
# A simple GitHub-friendly Python projec
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
    #!/bin/bash
# Simple script to update GitHub repository
# Usage: ./update.sh "your commit message"

# Step 1: Add all changes
git add .

# Step 2: Commit with message
if [ -z "$1" ]
then
  git commit -m "Update repository"
else
  git commit -m "$1"
fi

# Step 3: Push to GitHub
git push origin main

