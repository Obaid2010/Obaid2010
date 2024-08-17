print("Welcome To Your Computer Quiz!")
playing = input("Do you want to play? ")

if playing.lower() != "yes":
    quit()
print("Ok! Let's play :)")
score = 0

answer = input("What is the capital city of Morocco? ")
if answer.lower() == "rabat":
    print('Correct!')
    score += 1
else:
    print('Incorrect')

answer = input("What is the boiling point of water at sea level in Celsius? ")
if answer.lower() == "100°c":
    print('Correct!')
    score += 1
else:
    print('Incorrect')

answer = input("What is the largest planet in our solar system? ")
if answer.lower() == "jupiter":
    print('Correct!')
    score += 1
else:
    print('Incorrect')

answer = input("What is the chemical symbol for water? ")
if answer.upper() == "H²O":
    print('Correct!')
    score += 1
else:
    print('Incorrect')
print(f"You got {score} questions correct!")
print(f"You got {scor
