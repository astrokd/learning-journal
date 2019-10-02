# Read 03: HTML Lists, CSS Boxes, JS Control Flow

## From the Duckett HTML book:

Chapter 3: “Lists” (pp.62-73)
Chapter 13: “Boxes” (pp.300-329)

## From the Duckett JS book:

Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)

### Switch Statements
Switch statements live in one code block inside curly brackets.  Switch statements have a defaulkt value if none of the statements evauate as true.

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
```javascript
    var i;
    for (i = 0;i < 10; i++) {
        //Code goes here
    }
```
For loops are often used to loop through items in an array.

#### While
If you do not know how many times the code should run you can use a while loop.
```javascript
    var i = 0;
    while (i < 10) {
        //Code goes here
        i++;
    }
```

#### Do While
Like while but will always run statement inside curly braces atleast once even if condition is false.
```javascript
    var i = 0;
    do {
        //Code goes here
        i++;
    } while (i < 1);
```
