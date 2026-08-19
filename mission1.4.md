# math interpreter problem set:
def main():
    f = (input("what is x, and y, and z ?")).split(",")
    x = int(f[0])
    y = int(f[1])
    z = int(f[2])
    result = math(x, y, z)

    print(f"{result:.1f}")


def math(x, y, z):
    if y == ("+"):
        return x + z
    elif y == ("-"):
        return x - z
    elif y == ("*"):
        return x * z
    elif y == ("/"):
        return x / z
    
main()

there is some mistakes
better code=
def main():
    f = (input("what is x, and y, and z ?")).split()
    x = int(f[0])
    y = (f[1])
    z = int(f[2])
    result = math(x, y, z)

    print(f"{result:.1f}")


def math(x, y, z):
    if y == ("+"):
        return x + z
    elif y == ("-"):
        return x - z
    elif y == ("*"):
        return x * z
    elif y == ("/"):
        return x / z
    else:
        return ("invalid")
    
main()


points= i learned alot in this problem set=
we can use split function and then python will know that splited strs as an index then we can call that indexes and put them inside a variable and use them we
we cant change these * - + or other things like these to a int.
i learned how to call that index and use them
and tryed to use the f string again with this problem set

# meal time problem set=

