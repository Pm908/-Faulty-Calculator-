# -Faulty-Calculator-
The calculaor will exclude few operation.
Opp = input("Choose any operators [+, -, /, %, *]: ")
if not opp:
    print("Sir Plese enter the operator")
user1 = int(input("Enter your first number: "))
user2 = int(input("Enter your second number: "))
kak1 = user1 + user2
kak2 = user1 - user2
kak3 = user1 * user2
kak4 = user1 / user2
mod =user1%user2
if kak1 == 56 + 9:
    print(77)
elif opp == "+":
    print(kak1)
elif kak3 == 45 * 3:
    print(555)
elif opp == "*":
    print(kak3)
elif user1/user2 == 56 / 6:
    print(4)
elif opp == "/":
    print(kak4)
elif opp == "%":
    print(mod)
else:
    print(kak2)
