# Computer Quiz Game

This is a simple Python-based computer quiz game. Follow the instructions to play the game and test your computer knowledge!

## Code

```python
print("Welcome to my computer quiz!")

playing = input("Do you want to play? ")

if playing.lower() != "yes":
    quit()

print("Okay! Let's play :)")
score = 0

answer = input("What does CPU stand for? ")
if answer.lower() == "central processing unit":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What does GPU stand for? ")
if answer.lower() == "graphics processing unit":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What does RAM stand for? ")
if answer.lower() == "random access memory":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What does PSU stand for? ")
if answer.lower() == "power supply":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

print("You got " + str(score) + " questions correct!")
print("You got " + str((score / 4) * 100) + "%.")

-----
# How to run
Make sure you have Python installed on your system.
Copy and paste the code into a Python file (e.g., quiz_game.py).
Run the file in your terminal or IDE.
Answer the questions to see your score and percentage.


Features

Interactive question-answer format.
Keeps track of the user's score.
Displays percentage accuracy at the end.

Enjoy the quiz!
