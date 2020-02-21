# Programming with JavaScript

### Writting Scripts:
By now, we've learned how to create a web document structure with HTML and give it a little bit of flavor with CSS. Now that we have a working web page, we can use JavaScript, or JS, to make it come to life! JS adds an interactive layer to a web page. By writting scripts, we can add interactive elements that the user can engage with. So what is a script? A script is a recipe your computer will follow to do a specific thing. Just like a baker follows a cake recipe to ensure the end result is what he wants, your computer will follow the script you give it. So what does a script look like? Here's a small example:

```
var greeting = 'Howdy ';
var name = 'Molly';
var message = ', please check your order:';
var welcome = greeting + name + message;
```
What the above script is doing is creating variable for a welcome message. Variable? What are those? Variables act as storage containers in JS to strore a value we want to use later. So `var name` means we are declaring that `name` is a variable. What will the value be that we are storing in `name`? Looking back up at the exampe, the value we are asigning to `name` is Molly. If the example script were to run, it would assign values to the first two variable and concatinate, or combine, those values into a third variable. Printing out the ablve script would end with 
>"Howdy Molly, please check your order."

So your computer reads those "instructions" and does exactly what the script tells it to.

By default, your JS is on the global scale, meaning it will all run as soon as the browser reads it. This can be changed by using something called functions, which will be explained below.

### Expressions:

Expressions are another important part of JS. Expressions evaluate results into a single value. They will take values from multiple sources and output one value. So looking at the script example above, `var name = 'Molly'` is a basic expression. They can become much more complicated, but that all flows within the proper logic. If the logic doesn't make sense, the computer won't be able to make sense of the recipe. There are two basic forms of expressions:
* Expressions that asign a single value to a variable
```
var a = b
```
* Expressions that take multiple values to return a single value and then assign that new value to a variable
```
var a = b + c
```

Using expressions, you can expand on the above script example to make it more complex, giving you almost limitless options.

### Functions

Functions are an extremely versatile, very important part of writting JS. Functions take your code off of the global scale and encapsulate it inside of a function. First you must declare a function, `function 'give it a name'()`,
then using curly braces, `{}`, encapsulate your code below. Here's a small example of a basic function:
```
function howdy() {
     alert("This is a basic function!") 
}
```
When this function is called, it will popup with a notificaton saying 
>"This is a basic function!"

To call on a function, just add a HTML `<script>` tag and call the fucntion from the HTML document. That looks just like this:
```
<script>howdy()</script>
```
Simply use the name of the function, followed by (), and the script will run!