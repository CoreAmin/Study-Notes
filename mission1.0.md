day 1=
cs50p course
introduction:
we are going to learn
functions and variables
conditionals
loops
exceptions
libraries
unit tests 
file I/O
regular expressions
object oriented programming 
et setra:more tools for your toolkit 
additional building blocks
additional vocabulary 

lecture 0= functions and variables
hello.py= we created a python file named hello.py
then write our first python program this on: print ("hello, world")
functions= on of our functions is print or other thing
we have functions in most of the programming languages
arguments this is an imput to a function
and what that function does is depended to this argument
side effect= it can be visual it can be an audio
buges= the mistakes that we make in programming
we deleted one of the characters in this code print  ("hello, world"
and this gave us an error called syntax 
so the another function is input. we need to ask a user to right something in this.
and there is no need to right for example print ("what is your name") and after that write
input () we can write input ("what is your name? ")
here is the code= input ("what is your name? ")_print ("hello, Amin)
when we run this we will see this question in terminal and when we write our name there for example Amin after that the terminal will show hello, Amin but this is not true becuase we writed our name before in the string but right now we want to terminal show us what the user writed in input so
there is another thing called return values
and varibles ok so these varibles can save somthings in themseves this means we say to the computer this varible is for this sentence for example my name is ... = x from now when you want to print my name is ... there is no need to type all of this sentence inside print function you just have to write print (x)
so we need to do something here we are going to change the lines
we use = for varibles 
name = input ("what is your name? ")
print ("hello")
print (name)
this is not so professinal code we need to upgrade it
the other thing is named comments  why this exist somethimes the lines are too mush you you forget why you writed these thing so you need to write some note for yourself our any other person that will read your code the symbol for comments in python is # then you can comment what ever you want 
this is not good for little programs but making this a habit for yourself is good thing to know what your code is doing 
comments can be a to do list fot us
the other thing is pseudocode it is not a formal thing it is just your human language to express your thoughts succinctly methodically and algorithmically 
so today if is did not statred programming if i had a pseudocode for myself in comments i would write the same codes i did today
this is just for outlining step 1= ask the user for their name step 2= say hello to user 
ok so this way is so usefull because it breaks a bigger program down to small bite sized tasks
input is going to expect whats called string
alright right now we want upgrade our program to something professional
in python or any other languages there is so many ways to solve the same problem
ok we are going to delete the last line and change the other line to this
print ("hello," + name)
that is better right now
but if we add a space here it look more pretty
print ("hello, " + name)
write now there is another way to this you know we can put two or more arguments in one functions for example print how we can do this with this sign=, just this if you add this you can add a new argument right now we want to use this
print ("hello,", name) this will give us that same pretty result 
now witch one of these are better=
ok in previos verson i mean one argument the computer will do just like math rules 
that we have do what is in parentheses 
at 2 arguments we dont give the space the python will do it between the things
but in 1 argument we have to put that by ourselff 
and the difference between this and something we writed before= print ("hellow, Amin") and these two ways is that was hard coded that means we writed ourself before but these new ones are dynamic that means the python will get the result from the user then give that to function
+ = join what is at the right to the left

day 3=
str=string 
the other way to right the more professional code=
documentation of python = docs.python.org
learn to read the documentation
everything inside parantheses are arguments to function = parameters = values
these makes you to look in different ways
print(*objects, sep=' ', end='\n' , file=sys.stdout, flush=False)
*objects = print function can take any number of object
sep short for separator = multiple arguments= the are going to be sep by a space
end'/n' = when you pass arguments to print the hole thing will be ended with a new line

باز نویسی این موضوع بر اساس روش جدید نوت نویسی که یاد گرفتیم=
# subjects= Str - docs of the print function= every word or number that gets inside of "" or '' is string
# key words= string- documentation- arguments-parameters- star- seprate- end-
 practice= print("hello ,", end="")-print (name)
 print("hello ,", name, end="???") result= hello, ???Amin
 print("hello ,", namr, sep="???") result= hello,???Amin
# pints=what you can pass to a function these are parameters- when you use function and pass in values those inputs are arguments
# \n means new line

# subject= how we can put qoutes inside the print
questions fot paramerter= 2 kinds of parameters= positional - named
codes= print('hello, "firend"') - print("hello, \"firend\"")
points= backslash is an escape character
my mistakes= i put the / like this= print("hello, \"firend"\")

# subject= format sting = another way to solve the problem
key words= format string- curly brackets
codes= print(f"hello, {name}")
points= the f sign is a clue to python to format the stuff in special way

# subject= string methods for fixing the users mistakes while typing
key words= strip- methods-white space-
codes= name = name.strip()
points= there is a lot of functions that comes with strings in python.
second method= capitalize users name
code= name = name.capitalize()
point= capitaliza just is capitalizing the first letter
third method= capitalize every words first letter
codes= name = name.title()
method 3= we can chain these functions to each other
codes= name = name.strip().title()
more simple= at the first line do this= name = input("what is your name ? ").strip().title()
points= how much you simplify your codes and try to chain them together is more professional.

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