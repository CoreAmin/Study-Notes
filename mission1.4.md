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

## meal time problem set=
def main():
    x = (input("what time is it ? "))
    o = convert(x)
    if 7 <= o <= 8:
        print("breakfast time")
    elif 12 <= o <= 13:
        print("lunch time")
    elif 18 <= o <= 19:
        print("dinner time")



def convert(x):
    parts = x.split(":")
    hours = float(parts[0])
    minute = float(parts[1])
    return hours + minute / 60
    
    

if __name__ == "__main__":
    main()

points=
- this the last lines of code is like a lock for this code that says we can just use this code in this file
- this problem set is easy at the first look but it takes a lot of time to do all of the things that wants together.

# loops:
-for doing somthing again and again

## while:
this is a little like conditionals it is like while this is like this then do this
the awnser will be True or Fulse and while the awnser is True the python will run the program
and that is dangerous
codes=
x = 7 
while x != 0:
    print("hellow")
points=
- imagin a code like this because the x is not equal to 0 the awnser will be always
True so the computer will print hellow non stop this could damage your hardware
- using while is for the time we dont know what we are going to get from user
## the important shortcut for controlling:
when you lose the computer control working with these loops try to use:
- control + c

## so how we can fix this
this is like you ask any time is this like this
x = 7 
while x != 0:
    print("hellow")
    x = x - 1

- in this code we fixed the problem how:
in the indentation we are decreasing of number 7 every time and it will ask 7 times
and it will print the hellow 7 times too

## another way to solve this problem:
x = 1
while x <= 7:
    print("hellow")
    x = x + 1
points= here is how it works the x = 1 and we every time add 1 to that and the condition
of the program is less than and equal to 7 so it will add 1 to 1 seven times and it will print hellow 7 times too.

