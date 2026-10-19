# dict = data structure that allows you to associate one value with another
- a list is just a set of values but a dictionary is like two dimensional just like human
 dictionary. just like the words with theire definitions.


- take a look at this code we khow that the every name at the list for example index 3 is releated to food name inside index 3 in the other list but what will happen if the names get too much that will be diffcult to order these things under together all so now is the time we need to learn dictionary

 students = ["Alex", "Thomas", "Tyler", "Toby"]
 favorite_food = ["pizza", "pizza", "pizza", "pasta"]

 - for dict we need to use curly braces
 students = {
    "Alex": "pizza",
    "Thomas": "pizza",
    "Tyler": "pizza",
    "Toby": "pasta"
}
print(students["Alex"])
print(students["Thomas"])
print(students["Tyler"])
print(students["Toby"])

- the point is here is when we are useing list we call them by index number but here in dict we can use the the write word that is assosiate to another word in the other list

## can we use loops with the dict?
- when you use a for loop in python to iterate over a dictionary it iterates all of the keys

for student in students:
    print(students)

- now fot printing students name and theire favorite food we need to use this code:
for student in students:
    print(student, students[student])

points= so the students name is the key then this syntax: students[student] will give us the favorite foods of each of them in the dict

- we can add sep to make the result better:
 print(student, students[student], sep=", ")


- when you use a for loop with a dictionary you get to choose what the varible is called
 here it is student because it make sense 
 and here what the for loop does just like did with numbers before 0 and 1 and 2 
 this is very similar it itrate with the names instead of numbers it gives you more option.


# what if we have more information about each students:
- for example sauce name 
- what if we have a list of dictionaries 
 each of those students is itself a dictionary:

students = [
    {"name": "Alex", "favorite food": "pizza", "sauce": "tomato"}
    {"name": "Thomas", "favorite food": "pizza", "sauce": None}
    {"name": "Tyler", "favorite food": "pasta", "sauce": "alfredo"}
    {"name": "Toby", "favorite food": "pizza", "sauce": "mayonnaise"}
]

- None keyword for the place there is nothing for there for example here.

- ok write now if we want to use these with a loop:
for students in students:
    print(student["name"])

- here we ask to print the value of the name keys all of them:["name"]
-for student in students:
    print(student["name"], student["favorite food"], sep=", ")

here we add a comma to add to the print function arguments and seprated them with a comma and space.
- for student in students:
    print(student["name"], student["favorite food"], student["sauce"], sep=", ")

and this is just like the others.

