# JavaScript Tutorial

__Welcome__ to this complete [JavaScript](https://www.javascript.com/) tutorial, enough to get you kickstarted into learning the _complete_ JavaScript language.

## Course Content:
- What is JavaScript? 
- Where does JavaScript code run?
- Running JavaScript code on Google.
- Running JavaScript code on an editor.
- Installing Node.JS
- Actual coding:
    - Comments.
    - Variables.
        - What are variables?
        - Variables in JavaScript
        - Strings.
            - Escaping string literals
    - Arithmetic Operations
        - Addition
        - Subtraction
        - Division
        - Multiplication
        - Remainder
        - Incrementing
        - Floats
        - Augmented Operations
    - String Manipulation
        - Using single quotes
        - Escape Sequences
        - String Manipulation
        - Finding items in  a string.
    - Exercise 1
    - User Input
    - Converting Data types.
    - Arrays
        - Single Arrays
            - Accessing Array Data 
        - Nested Arrays.
            - Acessing Nested Array Data 
        - List manipulation.
            - `.push()`
            - `.shift()`
            - `.unshift()`
            - `.pop()`
    - Object literals
        - Accessing Object Data
    - Functions
        - Parameters and Arguments.
        - Global vs Local
    - Boolean values.
    - `typeof` to get data type.
    - If statements.
        - If statements' operators.
        - `and` and `or`
        - Else statements
        - Else if statements
    - While loops.
    - Switch Statements




# What is JavaScript?
*__JavaScript (often shortened to JS) is a lightweight, interpreted, object-oriented language with first-class functions. JS, was introduced by [Brendan Eich](https://en.wikipedia.org/wiki/Brendan_Eich) in 1995, and since has grown to be one of _the most_ popular programming languages for large companies like [FAANG(Big Tech)](https://en.wikipedia.org/wiki/Big_Tech) on an average salary of $70,000 in the U.S. With JS, you can become either a [Front-End-Developer](https://en.wikipedia.org/wiki/Front-end_web_development), a [Backend-Developer](https://en.wikipedia.org/wiki/Front_end_and_back_end), and even a [Full-Stack-Developer](https://en.everybodywiki.com/Full_Stack_Web_Development#:~:text=Full%20Stack%20is%20a%20layer,%2C%20database%2C%20server%2C%20etc.). 97% of the websites uses JS to interact with their pages. YEAH let that sink in __*.

_So, why not start learning it already when it is extremely easy to use and write the language?_

***
# Where does JavaScript code run?

*__JavaScript was initially designed to only run on browsers. On Mozilla, the JS Engine was called SpyderMonkey and on Google, it was called V8.  Up until 2009, this was the case, when an extremely clever engineer called [Ryan Dhal](https://en.wikipedia.org/wiki/Ryan_Dahl) took the open-source JS Engine in Chrome and embedded it into a C++ program. He called it Node. Soo, basically, Node is a C++ program that allows us to run JS outside of Google.__*

###### Hope, I haven't bored you yet. DW, the interesting part is starting lol.

***
# Running JavaScript code on Google

*__Now, I am going to show you how we can run JS on Google, like I said, using the JS Engine inside Chrome. So..__*
- *__Go to Chrome and right-click the main screen. __*
- *__Hit inspect__*
- *__Go to the console tab.__*

#### I assume everyone knows how to do this so I will not add pictures.

#### To test if your console is working, type in `console.log('Hello, World!');`. This is a little "Hello, World!" program in JS. Use it to test the console. You should see an output displaying: `Hello, World!` right under your line of code. 

** Note: It doesn't matter if you put the semi-colon or not, but it is best practice to put one. **


# Running JavaScript code on an editor

#### Now you can't just use google to run all your JS, beacause there is no way to properly save the code you write. For actual code compiling, debugging and plugins, we need a Code-Editor. There are amazing editors out there that you can download. Or you can just use the amazing [Replit](https://replit.com/~) IDE you are already on. Nevertheless, here are a few editors you can download:
- [VSCode](https://code.visualstudio.com/download)
- [SublimeText](https://www.sublimetext.com/)
- [Atom](https://atom.io/)

# Installing Node.JS
#### I would also recommend downloading [Node](https://nodejs.org/en/) as it is very useful and comes in handy when downloading "third-party-libraries" which are very helpful when developing apps and games using JS. For this tutorial though, I will be using Replit as it is the fastest, easiest and the best way to write Code efficently and quickly. So, if you haven't already, go make a Node.js Repl on your replit. Or [click here](https://replit.com/new/nodejs) to make one.


###### NOW!!! Let's get started with actually JavaScript learning and forget the boring stuff.


# Actual Coding:
#### Lets get started with learning JS:
***





## Comments.
I just wanted to add a little note about comments in JS. Comments in programming generally are a bunch of lines that are there to add context to code. They are not interpreted as code, rather they are ignored and are just there so that other programmars can see those comments and understand what is happening in the code. Comments in JavaScript are defined using two slashes, `//`. Here is an example:
```js
// This is a comment and will not be interpreted as code.
console.log("The comment is not code. YAYYY!!!");
```





***
## Variables

### What are variables?
Variables, the most important concept in JS and in any programming language, are used to store data temporarily in the computer's memory. So variable is we storing our data somewhere and allocating it with a name. With this, we can read the data at the given location  using the variable name later on and modify it the way we want. Think of variables like algebra. We assign a value to a variable like: `x = 5`. In this case, x is the variable. Here is a little metaphor to understand variables.:

#### _Let's say we have a few boxes. Each box contains things like stationery, books, devices, etc. Then to remember what box contains what, we put a label on each of the boxes, with keywords. __"Stationery", "Books" "Devices".__ This way, we remember what thing is in what container. Variables are the same exact thing, but in programming. In programming, the variables' name would be the labels, the value in the variable would be the box contents, and the memory allocated into the computer, would be the box itself. _
***
### Variables in JavaScript.
Up until the release of [ES6](https://en.wikipedia.org/wiki/ECMAScript), the standardized version of JavaScript, the practice of defining a variable in JavaScript was using the `var` keyword. But after its official release, defining a variable is best using `let`. There is a slight difference between these two keywords. The difference is the scope of the variable. The `var` keyowrd provides a global scope, meaning that it can be used in the entire function block. Where is `let`, is used in the _enclosing_ function block, meaning it can only be used in the function itself. For more info on this, read [this SO page](https://stackoverflow.com/questions/762011/whats-the-difference-between-using-let-and-var) that explicitly explains the differences between these two ways of defining variables.

Now, after we have written `let`, we can give a name or an identifier to our variable. This is the variable name. We can call it whatever we want as long as it meets the rules of defining a variable. There are a few ways you can define a variable. Here are the common conventions:
```js
// Using only the variable name without any space.
let name;

// Using two words separated by an underscore.
let my_name;

// Using two words using camelCase(First letter capital of each word except first.)
let myName;

// Using a word and a number without any space.
let name1
```
And these are rules that should be followed:
```js
// Cannot be a reserved keyword. These are keywords that are in JS like, let, var, if, etc.
// Should be meaningful, not just letters like a, b, x, etc.
// Cannot start with a number.
// Cannot contain space.
```

Now, if we use `console.log(name);` to actually print out the value associated with the `name` variable, we will see in the output, that it is undefined:
```
undefined
```

This is because there is no value given to the variable. To actually give a value to a variable, we have to use an `=` sign:
```js
// Giving the variable a value
let name = "John";
console.log(name);
```

Now, because the variable `name` is set to a string, `"John"`, the name's value is John. So when we print out the value of `name`, we will get the output as `John`:
```
John
```
BTW, the "John", the value set to name is called a string. A string is a sequence of characters. You can set it to anything you like and it will be printed out. A string can be either double quote, `"<string>"` or single quote, `'<string>'` . It evaluates as the same thing.
***

## Arithmetic Operations.
There are four main operations we learned in math:
- `addition` : `+` 
- `subtraction` : `-`
- `multiplication` : `×`
- `division` : `÷`

These are the normal symbols we use. But in programming, there is a slight difference. Division and Multiplication symbols are differenct and there are a few more operations. Here are the examples with the outputs:

- #### Addition:
    - ```js
    let addition = 3+2;
    console.log(addition);
    ```
    ##### Output:`5`

- #### Subtraction:
    - ```js
    let subtraction = 3-2;
    console.log(subtraction);
    ```
    ##### Output: `1`

- #### Multiplication:
    - The symbol for multiplication in JS is `*`
    - ```js
    let multiplication = 3*2;
    console.log(multiplication);
    ```
    ##### Output: `6`

- #### Division:
    - The symbol for division in JS is `/`
    - ```js
    let division = 4/2;
    console.log(division);
    ```
    ##### Output: `2`

- #### Finding only the remainder of a an improper division:
    - We can find _only_ the remainder of a division using the `%` symbol
    - ```js
    let remainder = 3%2;
    console.log(remainder);
    ```
    ##### Output: `1` . 
    Because, `³⁄₂` = `1 ½`, so 1 is the remainder

- #### Floats:
    - Floats are literally decimal numbers in JavaScript. They can also be referred to as doubles.
    - ```js
    let myFloat = 7.89;
    ```

- #### Incrementing.
    - You can add to variables using `++` or by simply using a number.
    - ```js
    let myNumber = 7;
    // Incrementing.
    console.log(myNumber + 3);
    ```
    ##### Output: `10` . 

- #### Augmented Operations.
    - Augmented Operations is basically using operations on variables defined to numbers.
    - ```js
    let a = 5;
    let b = 7;
    let c = 3;

    // Augmentation
    a = b + c
    b = a - c
    c = a * b

    console.log(a);
    console.log(b);
    console.log(c);
    ```
    
    ##### Output: 
    ```js
    10
    7
    70
    ```  
***



## String Manipulation
### Using single quotes.
When using a type of quote in a string, the quotes you use outside would be the opposite as not to confuse the IDE. Or you can use a backslash `\` to prevent this. Here are quick examples:
```js
// Using
let myString = 'This is my string using "double-quotes" and JavaScript does not get confused!!!';

let myString = "This is another string using \"backslashes\" and JavaScript does not get confused!!!"
```

### Escape Sequences.
Escape Sequences are used to manipulate a string using a backslash and a letter. There are 6 main escape sequences(other than the ones i already told you).
- #### `\n` Creates a newline:
    - ```js
    console.log("Hello\nJohn")
    ```
    Output: 
    ```
    Hello
    John
    ```

- #### `\r` Creates a Carriage return. Replaces the characters after the sequence with the ones behind the sequence.
    - ```js
    console.log("  llo\rHe")
    ```
    Output: `Hello`


- `\t` Creates a TAB.
    - ```js
    console.log("Hello...\tBYE")
    ```
    Output: `Hello...    BYE`

- #### `\b` Erases the previous character and replaces with the character after the sequence.
    - ```js
    console.log("Helli\bo")
    ```
    Output: `Hello`

- #### `\f` Forms a feed, i.e A `\n` with a `\t`
    - ```js
    console.log("Greetings\fHello")
    ```
    Output: 
    ```
    Greetings
              Hello
    ```

- #### Concatenating a string.
    - You can add two strings using a `+` operator.
    - ```js
    console.log("Hello, " + 'John')
    ```
    Output: `Hello, John`

- #### Concatenating a string using `+=`.
    - You can add two strings also using a `+=` on another line. You can also do this with variables.
    - ```js
    var ourStr = 'Hello, ';
    ourStr += 'John';

    console.log(ourStr)

    // adding variables
    var introduction = "My name is, ";
    var firstName = 'John ';
    var secondName = 'Smith';
    
    console.log(introduction + firstName + secondName);
    ```
    Output: `Hello, John`
***
### Finding items in  a string.
JavaScript allows us to find things in a string, for example the length of the string, the nth character, the last character etc.
- #### Finding the length of a string.
    - We can find the length of a string using `.length` in JS. It will return the number of characters in the string, including spaces if there are any.

    - ```js 
    var name = 'John';

    console.log(name.length);
    ```
    Output: `4`
    
- #### Bracket notation.
    - Bracket notation can be used to find the index of a character in a string. The brackets we use are squre: `[]` and the first index starts with the number 0.
    - ```js
    var name = 'John';

    // This will return the character at index 0, which is the first character, 'J'
    console.log(name[0]);
    // This will return the character at index 0, which is the second character, 'o'
    console.log(name[1])
    ```

## Exercise 1
This is an exercise for you. Here is the prompt:

#### Write a program that is going to use augmented operations to write a [BODMAS](https://www.mathsisfun.com/operation-order-bodmas.html) (Brackets, Orders, Division, Multiplication, Addition, Subtraction.) to print an answer of 9. Use the numbers 3, 6, 2, 8, and 4 **_only_**. Use variables from 'a' to 'e' for each of the number. Then use the variable `calculation` to do the math using the varaibles. Next, print out the following sentence in the exact fomat using string concatenation and escape sequences.
```
I used the numbers with "BODMAS" to find the answer of 9. 
The numbers used were:
3, 8, 6, 2, 4
```
** Note: Use only string concatenation. **

***

### Solution, Exercise 1.
Code:
```js 
let a = 3;
let b = 2;
let c = 6;
let d = 8;
let e = 4;

var calculation = ((a * c + d) / b) - e;

console.log("I used the numbers with \"BODMAS\" to find the answer of " + calculation + ".\nThe numbers used were:\n" + a + ', ' + b + ', '+ c + ', ' + d + ', ' + e)
```
Hope you got it. 
***

## User Input.
#### We can get user input in JavaScript using the `prompt` function, which is defined to a variable name. The prompt asks the user to input something. We can use that input to print out fancy things.
```js
var userName = prompt("Enter your name ")

console.log("Hello, " + userName + ". Welcome to JavaScript.")
```
#### So if we input `John`, we will get, `Hello, John. Welcome to JavaScript.`.
***
## Converting data types.
#### We can change an integer to a string and vice versa in JS. We can do that using the `parseInt` and `toString` methods. To do that, we can define a varibale, and use these functions to convert them into a different datatype.
```js
// Change string to integer:
var num = 9;
var n = num.toString();
console.log(n)

// Change integer to string:
var num = '9';
var n = parseInt(num);
console.log(n)
```

***
## Arrays
### Single Arrays
#### Arrays in JS are basically lists, that can contain items and can be modified. The syntax of writing an array is using a set of square brackets `[]`, and inside, the items separated by commas. Lets define an array:
```js 
// Array containing John's first name and his age.
var myArray = ["John",  21];
```
### Accessing Array Data 
#### We can access array data using the same way we access data and characters in a string. We can use the index of the list, once again, starting from 0.
```js
var myArray = ["John",  21]

console.log(myArray[0]) // -> John
console.log(myArray[1]) // -> 21
```


### Nested Arrays.
#### **_Nested Arrays_**, or **_Multi-Dimensional Arrays_** in JavaScript and in any other programming language, are a bunch of lists contained **_inside_** another list. The arrays in the larger array are treated as single elements and are separated by commas. Here is an example:
```js
// Nested list of my favorite movies/shows (not IRL lol) with their directors.
var myFavMovies = [["Alex Rider", "Andreas Prochaska"], ["Avengers: Endgame", "Russo Brothers"], ["The Matrix", "The Wachowskis"]]
```

### Accessing Nested Array Data 
#### Accessing data in Multi-Dimensional Arrays is the same as accessing elements in normal arrays, except first we need to refer the index of the list **_in_** the array, and **_then_** the elements in the list. Here is an example:
```js
var myFavMovies = [["Alex Rider", "Andreas Prochaska"], ["Avengers: Endgame", "Russo Brothers"], ["The Matrix", "The Wachowskis"]]

console.log(myFavMovies[1]) // Returns Second list in myFavMovies array.
console.log(myFavMovies[1][0]) // Returns Second list in myFavMovies array and then the first element in it.
```
#### This is helpful if we want to print out information from the lists into a nice statement like:
```js 
var myFavMovies = [["Alex Rider", "Andreas Prochaska"], ["Avengers: Endgame", "Russo Brothers"], ["The Matrix", "The Wachowskis"]]

// We can use this feature to print a statement:
console.log("\nOne of my favorite movies is " + myFavMovies[1][0] + ", directed by " + myFavMovies[1][1] + ".")
```
#### Output: `One of my favorite movies is Avengers: Endgame, directed by Russo Brothers.`

### List manipulation.
- #### `.push()`
    - #### We can add elements into an array in JavaScript using the `.push()` function. The `push()` function will ad an element to the end of an array. We know it is a function because of the parentheses in the end.
    - ```js
    let users = ['John', 'Ann', 'Mark'];
    // New user
    let newUser = 'Martin';

    users.push(newUser)
    console.log(users)
    // "users" will now be ['John', 'Ann', 'Mark', 'Martin' ]
    ```

- #### `.unshift()`
    - #### `.unshift()` is the same as `.push()` but, `.unshift()` adds elements to the start of the list.
    - ```js
    let users = ['John', 'Ann', 'Mark'];
    // New user
    let newUser = 'Martin';

    users.unshift(newUser)
    console.log(users)
    // "users" will now be ['Martin', 'John', 'Ann', 'Mark']
    ```

- #### `.pop()`
    - #### We can remove only the last element in an array using the `.pop()`. This will then return the same array without the lat element, so then the new array's last element will be the second last of the initial list.
    - ```js
    let users = ['John', 'Ann', 'Mark'];
    // New user
    users.pop()

    console.log(users)
    // "users" will now be ['John', 'Ann' ]
    ```


- #### `.shift()`
    - #### `.shift()` is the same as `.pop()` but it is the opposite. `.shift()` removes the **_first_** element from the array, not the last.
    - ```js
    let users = ['John', 'Ann', 'Mark'];
    // New user
    users.shift()

    console.log(users)
    // "users" will now be ['Ann', 'Mark' ]
    ```
***
## Object Literals 
#### Objects in real life are literally things that have propetrties, like a bag is an object, it's color is its property. The same way, objects in JavaScript are the same, but we use key:value pairs to define them. The value is defined to the key using a colon. This is an example of an object in JavaScript.
```js
let replitInfo = {
    yearFounded : '2016',
    placeFounded : 'San Francisco',

    funds : {
        funder1 : 'Andreessen Horowitz',
        funder2 : 'Y Combinator',
        funder3 : 'Bloomberg Beta'
    },

    founders : {
        ceo : 'Amjad Masad',
        coFounder1 : 'Faris Masad',
        coFounder2 : 'Haya Odeh'
    }
}

```
#### As you can see, you can have multiple objects in an object. And all new objects are separated by commas.

### Accessing Object Data.
#### We can access data in Objects using a `.` after the name of the object and referring to the key name, which would give us the value. So to access the place where replit was founded, the `placeFounded` key, we do this:
```js 
// Get a place where replit was founded
console.log(replitInfo.placeFounded)
```

#### This will return the value for `placeFounded`, which would give us `San  Francisco`. 


#### To access the data inside another object in the object, we will use the `.` to access the object, and then another `.` to access the keys inside that object.

```js 
// Get name of a funder.
console.log(replitInfo.funds.funder1)
```

#### So first we will access the `funds` object and then inside we will access `fund1`.


***
## Functions 
#### Functions are used to "encapsulate" a few lines of code that are meant to accomplish a specific task. Once a function is written, it can be used over and over and over again. Functions can be "called" from the inside of other functions. The syntax of defining a function is using a pair of brackets after the function name which comes after the keyword `function` and all the code that has to be executed in a pair of curly brackets.
```js 
function myFunction(){
    console.log("Hello, World");
}
```
#### Now if you run the program, nothing happens and that is because the function gets allocated into the computer's memory, but doesn't get called, and thus nothing happens. To actually interpret the code in the function, we need to call it.
```js 
// Create function
function myFunction(){
    console.log("Hello, World");
}

// Call functions
myFunction();
```

### Parameters and Arguments.
#### Arguments are values that can be input into the function that can be given when calling the function. Parameters are the values that is given by the arguments. Confusing? Let me explain practically.
```js 
function myAddition(a, b) { // a and b in the parentheses are the parameters.
    console.log(a - b)
}
// Now, we are going to pass in the arguments 
myAddition(10, 5)

// 10 is equals to a, and b is equals to 5. Up in the function, we did a - b, so we are basically doing 10 - 5.
```
### Returning a value from a function.

#### A return statement simply returns a statement. Instead of `console.log()`, we can just use return. Although, `console.log()` is a function used to print information to the console. return on the other hand is a call to pass some value back up to where the call was made. Here is an example:
```js 
function myAddition(a, b) { 
    return 'Two numbers are ' + b + " and " + a + "."
}

myAddition(10, 5)
```

### Global vs Local.
#### Global scope is when a variable is defined outside a function. This variable can now be used anywhere in the whole code, in any function. For example this code has a variable defined outside the `printNumber` function. So, it can be used in any function:
```js
var number = 6;

function printNumber() {
    console.log(number)
}

printNumber()
```
#### Local scope is when a variable defined in a function can only be used in the same function block, and will not work in other functions.
```js
function defineNumber() {
    var number = 6;
}

function printNumber() {
    console.log(number)
}

printNumber()
```

#### But here, we get an error : `number is not defined`, which is because the scope of the variable `number`, is only limited to the function `printNumber` .
***
## Boolean values.
#### Boolean values are simple values that evaluate to true, or false. They are basically like on and off switches, were on means true, off means false. All numbers return true, except 0 which return false.
```js
// Returns False
function myFalseFunc() {
    return false;
}

// Returns True
function myTrueFunc() {
    return true;
}
```

***
## Getting to know the data type.
#### We can know the data type of a variable using the `typeof`.
```js 
var aNumber = 9;
var aString = "Hello"
var booleanValue = false;

console.log(typeof aNumber);
console.log(typeof aString);
console.log(typeof booleanValue);
```
#### Output:
```js
number
string
boolean
```
***
## If statements.
#### If statements are basically conditionals, they are used to make decisions. If statements are english like and do something, if something is what we have set it to be. Here is how we would define an if statement. The `==` operator compares the value or equality of two objects. 
```js 
var number = 5;
// Literally means, if the number variable is true, do whatever is in the brackets.
if (number) {
    console.log("Number")
}
```
### If statements' operators.
#### Operators in if statements consists of `==`, `>`, `>=`, `<`, `<=`. These are just like math inequalities. Here is an example:
```js
var number = 5;
var number2 = 7;
var trueValue = true;

// If number is equals to 5.
if (number == 5) {
    console.log("Number is 5")
}
// Prints out "Number is 5" because number is set to 5.


// If number 2 is greater then 10:
if (number2 > 10) {
    console.log("Number is greater than 10")
}
// Prints out nothing because number2 is set to 7, which is smaller than 10.


if (number2 <= 10) {
    console.log("Number is smaller than or equals to 10")
}
// Prints out "Number is smaller than or equals to 10" because number2 is set to 7, which is smaller than 10.

// Will execute the code in brackets if value is true.
if (trueValue) {
    console.log("True Value")
}
```
**Note: _If we don't put any operator, then it is going to check the boolean value of the value and execute code if it is true._**

### Else statements.
#### Else statements do something if the previous conditionals do not meet the requirement. 
```js 
var age = 12;

if (age >= 18) {
    console.log("You meet the consent age.")
}

else {
    console.log("Nope, you are too old.")
}
```
#### "Nope, you are too old." will be printed out because age is less then 18 and all other ages under 18 will be ignored.

### The `&&` and `||`.
#### `&&` means `and` and `||` means `or`. `&&` compares all values and if they are true, the code will run. The `||`, will run if either of the given conditions evaluate to true.
```js
// "&&" example
let number = 32;

if (number > 20 && number < 40) {
    console.log("Number is smaller than 40 and greater than 20")
}   
```

```js 
// || example
let number = 32;
 
if (number == 25 || number < 40) {
    console.log("Number is smaller than 40 or equals to 25")
}  
```

### Else If Statements.
#### Else if statements are executed after the initial `if` statement.
```js
let number = 11;


if (number == 9) {
    console.log("Number is 9")
}   

else if (number == 11) {
    console.log("Number is 11")
}
```
***
## While loops.
#### A while loop will run as long as some conditional is true. While loops are english like. "While something is true, run this code."
```js
let num = 0;

while (num < 5) {
    console.log("Number is smaller than 5")
}
```
### But this will run forever an never stop. To stop the program once it has done what we want, we use a `break` statement.
```js
let num = 0;
// Will print "Number is smaller than 5" only one time.
while (num < 5) {
    console.log("Number is smaller than 5")
    break;
}
```
***
## Switch Statements
#### Switch statement are used to perform different actions in different conditions. They are basically used to avoid repetition of if statements. Here is the syntax of writing a switch statement, which is usually embedded in a function.
```js
function switchStatement(expression) {
    switch(expression) {
    case x:
        // runs this code block if expression equals to "x".
        break;
    case y:
        // runs this code block if expression equals to "y".
        break;
    default:
        // runs this code block if expression is not equals to any of the above cases.
    }
}
```
#### Lets make a switch statement that relies on user_input to print out the name of the day, relative to the number. Try it out yourself first. Here is my solution:
```js
var user_input = parseInt(prompt('Enter day number '));

function getDay(expression) {    
    switch(expression) {
        case 1:
            console.log('Monday')
            break;
        case 2:
            console.log('Tuesday')      
            break;
        case 3:
            console.log('Wednesday')      
            break;
        case 4:
            console.log('Thursday')      
            break;
        case 5:
            console.log('Friday')      
            break;
        case 6:
            console.log('Saturday')      
            break;
        case 7:
            console.log('Sunday')      
            break;
        default:
            console.log("No day on this number.")
    }
}

getDay(user_input)

```
#### Output: 
```
Enter day number > 7
Sunday
```

#### I used `parseInt` to convert the user input into an integer because it is initially a string.
***


# Conclusion:
#### I hope this course is enough to build your foundations on JavaScript and its syntax. There are many courses on YouTube that build more knowledge on these topics. Here are a few on Youtube:
- [FreeCodeCamp's](https://www.youtube.com/watch?v=PkZNo7MFNFg) Full JS Course.
- [Mosh Hamedani's](https://www.youtube.com/watch?v=W6NZfCO5SIk) Full Beginners JS Course.
- [Traversy Media's](https://www.youtube.com/watch?v=hdI2bqOjy3c) Full Beginners JS Course.
- [Clever Programmer's](https://www.youtube.com/watch?v=Qqx_wzMmFeA) 8 hours JS Course.
- [W3Schools](https://www.w3schools.com/js/DEFAULT.asp) Full JS Course.

### Credits:
Credits to @OldWizard209 and @0ldWizard209 's brain for contributing to 100% in making the tutorial. Also thanks to @Th3Coder for picking out spelling mistakes and asking me to add a few more touches. 

##### And also, there are tons of mistakes in grammar and spelling. So if you find any, tell me and I will fix it 🤙🤙🤙




