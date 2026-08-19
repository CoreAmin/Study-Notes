# subject= int = integers = the negative numbers and positive numbers
the other things like + - * / % are in use
points= the % is for the remainder after dividing the numbers to each other

# subject interactive mode = this is just for testing the code for example you want to see how a code works without saving.
open the full terminal then write just this= python the write anything you want

* little tips= 1= you can find your commands history in terminal with up and down buttons - 2= you can press tap after typing some of the first letters of some common words to complete that word fast.

# subject= creating calculator in python=
codes= 
x = 1
y = 2
z = int(x) + int(y)
print(z)
points= if you just write z = x + y it is going to know these as a srting not as a number so we need to add int function
if you dont put int function python is just going to add them together like 1 and 2 = 12 not like 3

# subject = one better way to solve last problem= you can chain the functions to each other so the return from the iner function will be an argument to the before function.
codes= x = int(input("what is x? "))
y = int(input("what is y? "))
print(x + y)
points= try to keep your code more simple how much it is simple to read is better chaining the functions or the codes is good but try to dont make it complicated too much.

# subject = float = decimal point numbers
codes= x = float(input("what is x ? "))
y = float(input("what is y ? ))
print(x + y)

# subject= to round the nearest int so this function is here = round
codes= c = float(input("what is c ? "))
k = float(input("what us k ? "))
z = round(c + k)
print(z)
points= the round juts takes one number as its first argument 
if you see these [] in docs you are going to see something opional 

# subject= trying to output this= ,     in big numbers like 1,000,000,000,000 just like this
codes= c = float(input("what is c ? "))
k = float(input("what us k ? "))
z = round(c + k)
print(f"{z:,}")
points = using {} and f says to python format this in another way

# subject= rounding the decimal point number until 2 or 3 number for example= 0.33 not 0.3333333
codes=
codes= c = float(input("what is c ? "))
k = float(input("what us k ? "))
z = round(k / c, 2)
print(z)

# subject = another way to do that= 
codes=c = float(input("what is c ? "))
k = float(input("what us k ? "))
z = c / k
print(f"{z:.2f}")
points= this looks wired but exist in docs

# subject= inventing your own functions=
codes= use def for define ===
def hello():
    print("hello")


name = input("what is your name ? ")
hello()
print(name)
points= for exampl you want to invent the function hello in python to not repeat the print("hello")
the : means for python to stay tuned that im going to give indentations for you and that 4 spaces are for text editor

# subject= parameterize our own functions
codes=def hello(to):
    print("hello,", to)


name = input("what is your name ? ")
hello(name)
points= alright so when we give parameters to a function like this if there is no other sign with that like*+_ this is just an empty place the hello function is waiting to see what word you want to give to put that instead of to for example here.
the parameter name is not important for python it just has a meaning for us 
ok so if you dont add any sign it is just an ampty place and of you add signs the python will change it depends on what sign is in your parameter.
my mistakes= i was thinking that when i writed the to as a parameter it has to get printed with the name for example= hello, to amin
but amin gets inside the to tha is known an empty place in function...

# subject= trying to get two awnsers from our own function
codes=def hello(to="world"):
    print("hello,", to)

hello()
name = input("what is your name ? ")
hello(name)
points= so here we say to the python if the parentheses are empty print hello world inside the [to] empty place- but if you fill inside the function when you are using it like hello(name) it is not going to fill the empty place with world

# subject = if you write your defining code under the the code that you want to use that function it is not going to work
points= this looks like you want define all the functions you want then start to coding start to using them but this looks bad we when we need to put our main code at the top of our defining function we must use main function
codes= def main():
....name = input("what is your name ? ")
....hello(name)

def hello(to="world"):
....print("hello,", to)

main()
points= the word main has just meaning for someone who read and its just a word to python.
that 4 spaces after defining function is just says to python dont run these things now and these are just inside of this function parameters and known functions these are just a map when i call this function then you can start runiung it the thing that is happening hers is this= first we build our first functuin and put the something we want from our next defining function inside it then we write our next defining function and order its parameters then call the function main to run the python will start by running from first code until the last beacuse its interpreter... when we run this code python will understand the functions then start to run them. we just created this main function to know where the main part of our code is.
my mistakes= i was thinking the python will start from the last line and run that in this kind of code
i was thinking this will give us an eror beacuse at line hello(name) he fuction hello is unknown but before running code the python read the functions and it knows what hello is then started running it

# subject = scope= when a variable exist in one function you can not use it in another function beacuse its unknown there if we write our variable out of our def function python will use it for all of the function but if we write that inside a function parameters that just will work when we call that function for example this is wronge=
def main():
    name = input("what is your name ? ")
    hello()


def hello():
    print("hello,", name)

main()

# subject= return =
def main():
    x = int(input("what is x ? "))
    print("square of the x is", square(x) )

def square(n):
    return n * n

main()