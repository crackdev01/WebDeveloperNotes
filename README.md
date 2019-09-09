# WebDeveloperNotes
This is a collection of reference material and notes on my journey to being a full stack web developer. 

## notes

This is a cheat sheet for beginners. This is for me to keep track of those things I use and want to keep track of. I hope you find it useful. 

## github markdown :octocat:

I enjoy writing README files for my projects. They are so useful and tons of fun to code! However, I keep losing the reference and every time I go to make one, I have to go hunt for it. Now I have it here. [click here](https://help.github.com/en/articles/basic-writing-and-formatting-syntax#using-emoji), for the MD reference. [click here](https://www.webfx.com/tools/emoji-cheat-sheet/), for the icon.

 Examples
 
 List: ```*li```           | *li <br>
 Bold: ```**B**```         | **B** <br>
 Italic: ```*B*```         | *B* <br>
 Link: ```[B](https://)``` | [B](https://) <br>
 Task: ```[ ], [x]```      | [ ], [x] <br>

## Callback Functions <br>
A callback function is a function that is passed into another function as a parameter then invoked by that other function. In a callback function you are gonna have 3 things. <br>
* A higher Order function. This function gathers the stuff to make it work.
* Callback. This function does the work, set outside of the HO function.
* Invoke. To do the work you laid out.

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

**.forEach** <br>
```function forEach(array, callback) {
    // To be Implemented
}```
