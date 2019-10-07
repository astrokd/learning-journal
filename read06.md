# Read 06: JS Object Literals; The DOM

[Understanding the problem domain is the hardest part of programming](http://simpleprogrammer.com/2013/07/15/understanding-the-problem-domain-is-the-hardest-part-of-programming)

The Problem Domain is the problem that the software, application, or tool is applicable to and trying to solve.

> Best to resist the temptation to “not waste anymore time talking” and make sure you understand a problem inside and out before you try and solve it with code. 

## From the Duckett JS book

- Chapter 3: “Object Literals” (pp.100-105)

An Object is a grouping of Functions and Variables.  As an object variables are called Properties and functions are Methods.

The Ways of Creating an Object
- Literal Notation
    -   Creating
        - var objectName = { list properties, declare functions/methods }
    -   Accessing
        - objectname.method-or-property
- Constructor Notation

- Chapter 5: “Document Object Model” (pp.183-242)
**aka the DOM**

The DOM is defined by the browser, it is not HTML or Javascript

> The Document Object Model, or the “DOM”, defines the logical structure of HTML documents & essentially acts as an interface to web pages. *medium.com, JavaScript Fundamentals: Master the DOM! (Part 1)*

Working with the DOM tree
- Step 1 Access the Elements
    - Select an Individual Element Node
    - Select Multiple Elements (NodeLists)
    - Traversing Between Element Nodes
- Step 2 Work With Those Elements
    - Access / Update Text Nodes
    - Work with HTML Content
    - Access or Update Attribute Values

Methods that find elements in the DOM tree are called DOM queries

- Methods that return a single element Node:
    - ```getElementById('id')```
    - ```querySelector('css selector')```
- Methods that return one or more elements (as a nodelist)
    - ```getElementsByClassName('class')```
    - ```getElementsByTagName('tagName')```
    - ```querySelectorAll('css selector')```

Once you select an element with a dom query you can edit its properties, or perform other methods on it.

You can loop through nodelists to perform actions

