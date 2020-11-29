# -
Лабораторна робота-Вступ до спеціальності

print("Hello world")

a= int (input("Введіть перше число:"))
b=int (input("Введіть друге число:"))
c=int(input("Введіть дію:\n 1 Додавання\n 2 Віднімання\n 3 Множення\n 4 Ділення\n"))
if c == 1:
    g=a+b
    print(g)
if c == 2:
    g=a-b
    print(g)
if c ==3:
    g=a*b
    print(g)
if c == 4:
    try:
     g=a/b
    except ZeroDivisionError:
     g="Ділити на 0 не можна"
     print(g)


for g in "Sun":
    print(g*2,end="")


for k in reversed("Juliana"):
    print(k)






