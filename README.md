This Repository contains all information related to the ISBOS JavaScript Club which meets Fridays at 3:30pm


The club's main goal is to look at programming in the real world (games, software...etc) and to do so, we examine basic programming concepts which are listed below:

# Variables
Just as in math, a variable is a symbol that references a different value over time. There are a variety of types that a variable can hold. These include, integers (5), strings ("hi"), booleans (True) and a few other types that we haven't covered as a group yet. Javascript is a dynamically typed language which means that to create a variable, you can just use the same keyword (var) for all variables. You do not have to specify the type that the variable holds. Instead, the computer will infer what type it is holding. 
Variables are central to programming. It is important that a variable has a good name. You should be able to look at someones code and understand it just based off the variable names. In this club, when we talk about variables, we say "They hold something". 


#### Code Examples

```javascript
var x; //This creates a variable called x
x = 5; //This sets the value of variable x to 5
var t = "hi"; //This creates a variable called t and sets its value to "hi"
r = "sam"; //This is invalid because a variable named r hasn't been created yet
```

#### More Information

[w3 Schools JavaScript Data Types] (http://www.w3schools.com/js/js_datatypes.asp)
[w3 Schools JavaScript Variable] (http://www.w3schools.com/js/js_variables.asp)
[w3 Schools JavaScript Variable Scope] (http://www.w3schools.com/js/js_variables.asp)


# Function
A function is a block of code that is designed to complete a task. A function must be defined somewhere in your code. This means that you tell the computer what a function does. When you "call" a function, it jumps to the section of code where a function is defined, executes it, and then returns back to the original place in the code that was being exectuted. A function accepts arguments when it is called. These arguments are variables that the function then does something with.

#### Code Examples

```javascript
//This function accepts two numbers as its arguments, adds them together and then returns the sum
function add_two_numbers(num1, num2) {
	var sum = num1 + num2;
	return sum;
}

var t = add_two_numbers(5,6); //This is how you would "call" the add_two_numbers function. This will add 5 and 6, and store the result in a variable
var a = 4;
var b = 6;
var c = add_two_numbers(a,b); //This will add the values of the variables a and b, and store the result in c. Since a holds 4 and b holds 6, c will hold 10

```

#### More Information



