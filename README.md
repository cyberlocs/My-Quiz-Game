print("Welcome to name that show quiz!")

playing = input("Do you want to play? ")

if playing.lower() != "yes":
    quit()

print("Okay! Let's play :)")
score = 0

answer = input("Homer Simpson? ")
if answer.lower() == "the simpsons":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("Peter Griffin? ")
if answer.lower() == "family guy":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("Raven Baxter? ")
if answer.lower() == "thats so raven":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("Penny Proud ")
if answer.lower() == "the proud family":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

print("You got " + str(score) + " questions correct!")
print("You got " + str((score / 4) * 100) + "%.")
