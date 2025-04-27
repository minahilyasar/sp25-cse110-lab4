## part1-question1:
values added:  20
## part1-question2:
final result:  20
## part1-question3:
Since variables defined by var are accessible throughout the whole function, even before they have been declared, it can cause confusion. Moreover, they can also be overwritten if declared with the same name in different parts of the function. 
## part1-question4:
values added:  20
## part1-question5:
This causes a ReferenceError: result is not defined error. This is because result was declared in the if block using let and it is not accessible outside of that block. When it is called in line 13, there is an error as it is outside the if block.
## part1-question6:
Line 7 causes TypeError: Assignment to constant variable. Declaring a variable using const means it cannot be reassigned, hence causing the error. There is no output for line 9 as JS stops executing after an error.
## part1-question7:
Since line 7 causes the error, there is no output for line 13 as JS stops executing after it.