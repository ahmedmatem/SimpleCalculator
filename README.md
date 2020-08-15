# SimpleCalculator
A simple arithmetic expression calculator
Object oriented programming (OOP) is a programming concept based on objects, which are used to model the real world. An object contains data in fields often known as properties or attributes and functionality in the form of procedures often known as methods.
The OOP paradigm allows us to arrange the objects in the model in a hierarchy that represent “is-a-type-of” relationships. 
Encapsulation, composition, inheritance and polymorphism are some of the base concepts in OOP paradigm that can be used to associate real-world objects and processes with digital counterparts.

 Simple calculator:
 ![calculator](https://github.com/ahmedmatem/simplecalculator/blob/master/calc.png?raw=false)
A simple calculator with arithmetic operations can be realized with the help of object-oriented programming.
Calculator contains a display and keys. Display shows the arithmetic expression entered by the user with pressing keys and the result of the calculation after pressing “=” key (SubmitKey).
Тhe user presses the keys on the calculator to enter a simple arithmetic expression (for example: 12+3*4) and the "=" key (SubmitKey) to calculate and print the result on the display. 

All keys have an action() method that triggers after an on click event. When a digit key is clicked by the user action method of DigitKey just print a symbol on the display. When an arithmetic operator is clicked OperatorKey onClick handler does the same as DigitKey action method plus adding and saving pressed operator (+, - or *) for next calculation use. There are two RedoKey/s that are used by the user to clear the last symbol or entire expression from display.  This happens again in the action method of RedoKey by printing(deleting last or all symbols) propper symbols on display. After the arithmetic expression has entered, the user clicks on Submit Key (“=”). Again the action method of the Submit key will be triggered and proper action of calculation will happen and result will be displayed.

