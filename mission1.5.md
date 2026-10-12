## we can do this instead of i = i + 1
- i += 1

## for loop
codes=
for i in [0, 1, 2]:
    print("hello")

points=
- the for loop is more simple than while 
- when we know how many times we are going to do it use for
- but sometimes you dont know the awnser the input from user so you need to use while
- the list in this pr is this [0, 1, 2]
- when you use [] this is a like a list sign for python

## list 
- this is a nother data type python supports


## the problem of the fisrt code about for loop
- it is not possible to write for example 1000 you shoude write all of the numbers in list so
## the solution
- use the function range
codes=
for i in range(100):
    print("hello")

points= the name of variabe is not important here you can name it - for example instead of i becuase you are not going to use it.

# another instresting way to do this is this it is just for python
codes= 
print("hello" * 3)
- use \n for printing hellow in a new line every time \n means a new line
- or use this end=""     print("hello\n", end="")

## now we want to ask user to knwo how many time we shoude print hellow
- imagin you want a user to input positive number it is not possibe to every time if number is this then ask again
so we need to use loops here to ask the user to input again if the number is not positive with the loops not with if or else

key words= while True-continue-break

while True:
    n = int(input("what is n ?"))
    if n < 0:
        continue
    else:
        break

- more simple:

while True:
    n = int(input("what is n ?"))
    if n > 0:
        break


- 
while True:
    n = int(input("what is n ?"))
    if n > 0:
        break

for _ in range(n):
    print("hello")


- so write here we made a code to print the hellow as the users input.


# defining functions for loops examples:

- def main():
    hello(3)

def hellow(n):
    for _ in range(n)
    print("hello")

main()

point= here we writed the 3 now how we can get a number from user we need to make another function:

- def main():
    x = what_is_number()
    hellow(x)

def what_is_number():
    while True:
        w = int(input("what is x ? "))
    if x > 0:
        break
    return n

        
def hellow(n):
    for _ in range(n)
    print("hello")

main()


- here is what we must use return but you can use break and after that write return n both of them are true.
    

# usuing lists with loops

- how to print contemts of a list the awnser is calling indexs
 students = ["Alex", "Thomas", "Tyler"]
 print(students[0])
 print(students[1])
 print(students[2])

- we can use a loop here
 students = ["Alex", "Thomas", "Tyler"]
 
 for student in students:
     print(student)

 points= write here we had this ability to write:
 
 for _ in students:
     print(_)

but the previos verson was better. because its more readable

# len functions: this will tell you the length of the list
- renage does not take the list of strings it takes the numbers so this is where the len function workes
- example:

 students = ["Alex", "Tomas", "Tyler"]

 for i in range(len(students)):
     print(students[i])

points= i did not learn well this one there is need to more practice

- students = ["Alex", "Thomas", "Tyler"]

for i in range(len(students)):
    print(i, students[i])

points= here when we run this it shows Alex in index 0 to user there is no need to show this like this so:

print(i + 1, students[i]) 

# Review for loop:
- this creates you a variable called i or you can name it whatever you want
- for example: for i in [1, 2, 3]
 this is a loop you are saying to this loop right here to do this 3 times
 this for loop first assigns i for the first thing in the list the seconde and third
- then we learnt range for not writing all the numbers inside the list on by on that is difficult.
 it returns us a range of values
- now there is combining these things with len function becuase the rang does not support strings ok
 we want to do a range of values but how many values so we use len and pass the list of values to that
 the len function is just saying how long is this list we had the ability to just write 3 but we dont want to hard code it
 we want to this happen automatically