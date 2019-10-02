# Read 03: HTML Lists, CSS Boxes, JS Control Flow

## From the Duckett HTML book:

Chapter 3: “Lists” (pp.62-73)
Chapter 13: “Boxes” (pp.300-329)

### Lists
```HTML
    <ol> <!-- Ordered list -->
        <li>list item</li>
    </ol>
    <ul> <!-- Unordered list -->
        <li>list item</li>
    </ul>
    <dl> <!-- Definition list -->
        <dt>Term</dt>
        <dd>Definition</dd>
    </dl>
```
List can be nested inside one another.

### Boxes
CSS treats each HTML element as if it lives in it's own box
Box dimensions
```
    width: 300px;
    height: 300px;
```
Limiting Width
```
    min-width: 450px;
    max-width: 650px;
```
#### Border, Margin, & Padding
Border: every box has a border, the border separates one border from another

Margin: outside the edge of the border, creates space between adjacent boxes

Padding: space betwwen border and content of box
```
border-width
border-style
border-color
border
padding
margin
```
If you want to center a box on a page to can set left-margin and right-margin to auto.
The display property allows you display a li elements in a row or line
```
display
```
visibility lets you hidden elements

border-image lets you use an image as a border

border-radius lets you round box corner
border corners can have elliptical shapes

## From the Duckett JS book:

Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)

### Switch Statements
Switch statements live in one code block inside curly brackets.  Switch statements have a default value if none of the statements evauate as true.
``` Javascript
    switch (level) {
        case 'One':
        title = 'L1';
        break;
        case 'Two':
        title = 'L2';
        break;
    }
```


IF...ELSE vs SWITCH
Switch statements have a break so once a condition is meet they leave the statment providing better performance, IF ELSE each statement is checked no matter what.

### Type Coercion
strings can be converted to numbers in expressions, for example `'1' > 0` is evauluated as true.

### Truthy and Falsy Values
The existence of a value is considered truthy

Falsy values are things like;
 ``` JS
 var score = false; //boolean false
 var score = 0;  //number zero
 var score = '';  //empty value
 var score = 10/'score';  //NaN
 var score;  // no value
 ```

Strict equality operators (=== and !==)result in fewer unexpected values than the non strict ones (== and !=) 
For example; `0 == ''` is true and `0 === ''` is false.

Short Circuit Values
Logic operators are processed left to right as soon as they have a result they return the value of the result.

### Loops
Loops check a condition, if it returns true the code block is run then the condition will be checked again.  As long as the condition returns true the loop will continue to repeat.

#### For
Uses a counter as a condition each time the code block in the for loop is run the counter is updated.
```Javascript
    var i;
    for (i = 0;i < 10; i++) {
        //Code goes here
    }
```
For loops are often used to loop through items in an array.

#### While
If you do not know how many times the code should run you can use a while loop.
```Javascript
    var i = 0;
    while (i < 10) {
        //Code goes here
        i++;
    }
```

#### Do While
Like while but will always run statement inside curly braces atleast once even if condition is false.
```Javascript
    var i = 0;
    do {
        //Code goes here
        i++;
    } while (i < 1);
```
[Readme learning journal](README.md)