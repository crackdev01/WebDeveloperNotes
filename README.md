# WebDeveloperNotes
This is a collection of reference material and notes on my journey to being a full stack web developer. 

## notes

This is a cheat sheet for beginners. This is for me to keep track of those things I use and want to keep track of. I hope you find it useful. This list is gonna continue to grow as I keep learning, so I am making an index here. At some point I will move this to the back and put in a table of content. Maybe after I get a little content.

- Github MD
- Java Script

## github markdown :octocat:

I enjoy writing README files for my projects. They are so useful and tons of fun to code! However, I keep losing the reference and every time I go to make one, I have to go hunt for it. Now I have it here. [click here](https://help.github.com/en/articles/basic-writing-and-formatting-syntax#using-emoji), for the MD reference. [click here](https://www.webfx.com/tools/emoji-cheat-sheet/), for the icon.

 Examples
 
 List: ```*li```           | *li <br>
 Bold: ```**B**```         | **B** <br>
 Italic: ```*B*```         | *B* <br>
 Link: ```[B](https://)``` | [B](https://) <br>
 Task: ```[ ], [x]```      | [ ], [x] <br>

# Basic JS

**Data Types:**

- String = characters, '', ""
- Number = digit, 1, -1, .5
- Boolean = true / false, on / off

- defined = is set, this is known
- undefined = spot in memory, no value
- null: empty. No value

String is sequence of characters, letters. Associate quotes with string. Number is not picky. Can be any type of number. positive, negative, fraction, etc. Boolean is a switch. Will either be yes or no. Get data typr with typeOf: _example: var a = 500; typeOf a will return number_

**Variables**

- var: use least (old), use at base scope (never in function)
- let: (newer), variable can be modified after set. (use in function)
- const: (newer), variable can not be changed once set. (always use this)

first character can not be a number. can not declare keywords as variables. Declare multiple variables with comma separation. _example: var a = 'a', b = 'b', g = 50;_

**Operators**

- = assign
- + add
- - subtract
- /* multiply
- // divide
- % Modulus
- ++ increment
- -- decrement


**Different case types**

camelCase
KaBobCase


## Callback Functions <br>
A callback function is a function that is passed into another function as a parameter then invoked by that other function. In a callback function you are gonna have 3 things. <br>
* A higher Order function. This function gathers the stuff to make it work.
* Callback. This function does the work, set outside of the HO function.
* Invoke. To do the work you laid out.
A higher order function is a function that accepts a callback as a parameter.

**_example_**
```
function higherOrder(fn) {
    console.log('About to call callback');
    fn(); //callback function invoked
    console.log('Callback has been invoked');
}
function callback() {
    console.log('coming from a callback');
}
higherOrder(callback);
```
## JS Loops

**.forEach**
```
function forEach(array, callback) {
    // To be Implemented
}
//callback signature
function callback(curElement, currentIndex, array) {
    //Implemented by the caller of forEach
}
```