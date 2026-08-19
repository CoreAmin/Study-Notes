the new functions and thing that are in problem sets of first video=
.lower() function for changing users input to lowercase all of the words and letters 
.replace() very usefull function to change something we dont want in users input
and then we worked with these functions in the projects in these problem sets for example building a program for e=mc2 square c i mean. and completed a program that allows people to know how much tip they want to give if its 7 dollers and they want to give 10 percent the result will be 0.7 these problem sets were making us to work with different functions togheter and try to search and find a function name from internet or other things
-------------------------------------------------------------------------------------------------------------------------------------
# conditionals= these are for ask questions and awnser does questions based what the user did or run on part of the code based of the users input. more simple we are going to say to python do this if this happend do this if it did not.
the symbols to do this=
    > greater than
    >= greater or equal to
    < less than
    <= less than or equal to
    == equal
    != not equal
    
# the main keywords for conditional= if
codes=x = int(input("what is x ? "))
y = int(input("what is y ? "))

if x < y:
    print("x is less than y")
points= here the x < y is a boolean expression there is no need to parentheses but we need colon and that four space at the next line
we can add more lines for example if x > y then print x is greater than y or other thing
so we understood the python will read all of the lines and if the awnser to the if is true will run what we wrote. but if it was false will then it will not it will just move to the next line to read

# elif keyword to ask and run boolean questions
codes= x = int(input("what is x ? "))
y = int(input("what is y ? "))

if x < y:
    print("x is less than y")
elif x > y:
    print("x is greater than y")
elif x == y:
    print("x is equal with y")

points= alright when we look at these code we understand that if we run our code with only if the python will read the next lines after running the first print if the awnser were true but just like here if we write elif in our codes if the python get the true awnser it is not going to continue to read other elifs and it will finish but if the awnser was false it is going to read the true awnser until it get the first true awnser and then finish.

....so if we use if it is going to read all of the but if we use elif if python find first awnser it is not going to reading.

# else keyword to finish the boolean program= this is saying to python=
if the awnser is this then do this
elif is this do this
but if the awnser is something else then do this
codes=
x = int(input("what is x ? "))
y = int(input("what is y ? "))

if x < y:
    print("x is less than y")
elif x > y:
    print("x is greater than y")
else:
    print("x is equal with y")

points= this is what logicly happening here in math if one if the two different numbers was not greater or less than the other they are equal

# or keyword: this give us more tools to use in boolean things...
codes=
x = int(input("what is x ? "))
y = int(input("what is y ? "))

if x < y or x > y:
    print("x is not equal to y")
else:
    print("x is equal to y")

# how we can make this code more simple is better right now we can ask python is this equal to that or not instead of checking this is greater or not
codes= we can use this
if x != y:
    print("x is not equal with y")
else:
    print("x is equal to y")
or
if x == y:
    print("x is equal to y")
else:
    print("x is not equal to y")

# and keyword this gives more options to you 
for example look at this code that i build by myself=
score = int(input("how many push ups you can do ? "))

if score < 10 and score < 20:
    print("you are bigginer")
elif score > 20 and score > 30:
    print("you are intermediate ")
elif score > 40 and score > 50:
    print("you are pro")
else:
    print("print you are legend")

this code is wronge and after i fixed it:
score = int(input("how many push ups you can do ? "))

if score <= 10 and score <= 20:
    print("you are bigginer")
elif score > 20 and score <= 30:
    print("you are intermediate ")
elif score > 30 and score <= 40:
    print("you are pro")
else:
    print("you are legend")

my mistake= as we know the python in elif codes will not read the rest of the code if it find the first true awnser and in the first code that was not possible to find false awnser and it was going to finish at the first line but i fixed that.

looks like there is another problem in my code the new code=

if score <= 20:
    print("you are bigginer")
elif score <= 30 and score <= 40:
    print("you are intermediate")
elif score <= 50 and score <= 60:
    print("you are pro")
else:
    print("you are a legend")

Alright another mistake lets try again=
score = int(input("how many push ups you can do ? "))

if score <= 20:
    print("you are bigginer")
elif score > 20 and score <= 40:
    print("you are intermediate")
elif score > 40 and score <= 70:
    print("you are pro")
else:
    print("you are a legend")

Alright this one is perfect=
the main point at my mistakes was this that i wanted to say to python if this number is less than or equal to 30 do this then if its less than or equal to this do the same thing it looks like you want someone be in two places in one time so it was working to numbers between 21 until 30 but it was not working to number between 31 until 40
and in the progress i found the communications between these less than or greater than in these kind of booleans

# the job that i have done here is i did not copy the teachers code and im getting chalenged a little bit but no problem we are here to learn and fix this


ok so the next lesson is this that how we can simpify these code better=
im gonna write another code by myself
codes



Alright today we dont have any new code.because today i fucuced on the writing new codes like this=
cigarets = int(input("how many cigarets do you use every day ? "))

if 30 <= cigarets and cigarets <= 40:
    print("you are a chain smoker")
elif 20 <= cigarets and cigarets <= 30:
    print("you are addicted to cigaret")
elif 10 <= cigarets and cigarets <= 20:
    print("you are getting addicted please dont do it again")
elif 1 <= cigarets and cigarets <= 10:
    print("never continue")
else:
    print("looks like leaving cigarets will be really hard to you")

this code is wronge an today i was exploring to understand why and i figured out too much but what i learnt about the commnucations between <==> and if and elif and else is not to enough to write a new code about this new lesson. so im gonna stop here and we will continue learning about these in next week until we understand everything.