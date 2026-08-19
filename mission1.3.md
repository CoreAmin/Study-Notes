# we are going chain the booleans together. and use and without writing it
score = int(input("what is the score ? "))

if 90 <= score <= 100:
    print("grade A")
elif 80 <= score < 90:
    print("grade B")
elif 70 <= score < 80:
    print("grade C")
elif 60 <= score < 70:
    print("grade D")
else:
    print("grade F")
points= here we swiched the 90 with the score and as you can see we are using and without writing it

# lets simplfy this more:there is no need to write greater than or less than this then print this
score = int(input("what is the score ? "))

if score >= 90:
    print("grade A")
elif score >= 80:
    print("grade B")
elif score >= 70:
    print("grade C")
elif score >= 60:
    print("grade D")
else:
    print("grade F")

# lests bulild a code that says this number is even or odd
x = int(input("what is x ? "))

if x % 2 == 0:
    print("Even")
else:
    print("Odd")

# the boolean values can be True or False
points= it must be capital T and F at beggning of the words

# build the function to say us this number is even or not

def main():
    x = int(input("what is x ? "))
    if is_even(x):
        print("Even")
    else:
        print("Odd")

def is_even(n):
    if n % 2 == 0:
        return True
    else:
        return False

main()

points= 

# how we can build this better more simple:
def main():
    x = int(input("what is x ? "))
    if is_even(x):
        print("Even")
    else:
        print("Odd")

def is_even(n):
    return True if n % 2 == 0 else False

main()
points= here we must write return at the beggning

# more simple 

we can write the code like this
retrun n % 2 == 0
points= here there is no need to ask if or else. this question n % 2 == 0 has two awnsers
True or False so there is no need to ask that again. so this one is more simple.
one important thing to know is this that if elif and else are like toolcase and True False or and == <> % / * or other things like these are tools 

# another important thing: if we use or in our boolean the python will give True awnser to that thing when it find the first True awnser but if we use and all of that thing have to be True not one of them

# match keyword: the diffrence between this and if elif and else is this they look for to find out is this true or not this one looks for to find out is if this have that detail and shape then unpack and name the things inside it and give me them out
# the match is not in if elif and else group and has rules for itself but it looks fimalier with them sometimes.
 codes=
  name = input("What's your name? ")

  match name: 
      case "Harry":
          print("Gryffindor")
      case "Hermione":
          print("Gryffindor")
      case "Ron": 
          print("Gryffindor")
      case "Draco":
          print("Slytherin")
      case _:
          print("Who?")

points= _ here means like else


____= my awnsers to the problem sets=
# deep thought=
x = input("what is the awnser to the great question of life, universe and everything ? ").strip().lower()
if x == ("42") or x == ("forty-two") or x == ("forty two"):
    print("Yes")
else:
    print("No")
# home federal savings bank=
x = input("please have a greeting with me ? ").strip().lower()
if x.startswith("hello"):
    print("0")
elif x.startswith("h"):
    print("20")
else:
    print("100")

points= i learnt the startswith function here to point to python one special thing in str that starts with.

# file extensions=
for writing this program we need to figure out what are these functions=
rfind=for example we want to point to python where is the last - in on of the str= use this .rfind("-") here the python will know witch number syntax is this charachter - is it 4 or 5 then you can ask that to do other thing with that for example the name of the variable of the str is x so print([x:])
rsplit= here is the next function this is for spliting a str for example a str is this car.png you write this code .split(".", 1)
here the number 1 says to python split just one time from that point now we can say to python what to do with that them
codes=
file_name = input("what is name of the file ? ").strip().lower()
number = file_name.rfind(".")
file_type = file_name[number:]
if file_type == (".gif"):
    print("image/gif")
elif file_type == (".jpg") or file_type == (".jpeg"):
    print("image/jpeg")
elif file_type == (".png"):
    print("image/png")
elif file_type == (".pdf"):
    print("application/pdf")
elif file_type == (".txt"):
    print("text/plain")
elif file_type == (".zip"):
    print("application/zip")
else:
    print("application/octet-stream")

my mistakes= in this project i get challenged a little here is the mistakes=
i was making mistakes in rfind function alot this function finds a number in our str and we must say to python what to do with that number in a variable. first we must get the input then find a number in a variable then say to python what to do with that im another variable then we can use it in if and elif for slcing tthe the str after that number we must use this file_name[number:]
most of my mistakes in this part was for forgeting the rules of this function and trying to use just number not sliced str and this was a mistake.

other problem sets for next mission...