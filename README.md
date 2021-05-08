# love_calculator
print("Welcome to the Love Calculator!")

name1 = input("What is your name? \n")
name2 = input("What is their name? \n")

combain_name = name1 + name2
love_case_string = combain_name.lower()

t = love_case_string.count("t")
r = love_case_string.count("r")
u = love_case_string.count("u")
e = love_case_string.count("e")

true = t+ r + u + e

l = love_case_string.count("l")
o = love_case_string.count("o")
v = love_case_string.count("v")
e = love_case_string.count("e")

love = l + o + v + e

love_score = int(str(true) + str(love))

if love_score < 10 or love_score > 90:
 print(f"Your love score is {love-score}, you are like coke and mentos.")
elif love_score >= 45 and love_score <= 50:
 print(f"Your love score is {love_score}, you are alright together.")
else:
 print(f"Your love score is {love_score}.")
