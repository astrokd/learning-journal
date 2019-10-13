# Class 10 Debugging
Finding errors in your code

Console.log varaibles

`debugger;` line in code will let you pause and step through code

DRY
 create function called addElement

 ```Javascript
 function addElement(childElType, childContent, parentEl) {
  var childElement = document.createElement(childElType);
  childElement.textContent = childContent;
  parentEl.appendChild(childElement);
  return childElement
}
```
[Readme learning journal root](README.md)