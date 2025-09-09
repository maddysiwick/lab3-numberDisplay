Project: number-display
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class NumberDisplay. Then inspect this 
instance and leave the inspector window open. With the inspector window open, 
call the object's methods, such as increment and setValue.

1. diagrams are in the project folder
2. A class diagram could change if new classes were added to the project or relationships were created between classes
3. an object diagram would change if new instances of a class are created, or if they are
linked to another object (ex: enrolling students in a LabClass)
4. private Instructor tutor;
6. you should check if the value is zero, as that would mean it rolled over and it is time to increment 
the hours display
8. no, because there is a condition set to ensure that it will only change the value if it is positive and below the 
limit. If both of these conditions are not met, it will never reach the statement resetting the value.
9. It will not reset the value as 10<10 is not true
10. Error: non-static method getValue() cannot be referenced from a static context
11. you should only specify the type when declaring a variable, when you are passing a value like in this case,
it will return an error (I think that's what's wrong)
13. 0
14. any invalid value would be set to the field as they are all either positive (replacementValue>=0) or less than the limit
(including negative)