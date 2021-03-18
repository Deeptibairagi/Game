# Game
Number Guessing Game


Lucky_number = 30
guess_num=1
print("Number Guessing Game between 1 to 50\n")
while guess_num<=9:
    num1 = int(input("Enter a lucky number\n"))
    if num1 == 30:
        print("Congratulations you have win the game, Total number of Guess is ", guess_num )
        break
    elif 30 < num1 <= 50:
        print("it is big number\nNumber of Guess left", (9-guess_num))
    elif 0 < num1 < 30:
        print("it is small number\nNumber of Guess left", (9-guess_num))
    else:
        print("out of range")
    guess_num=guess_num+1
if guess_num>9:
    print("Sorry Game over")
