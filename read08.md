# Read 08: HTML Forms, CSS Data Styling, JS Events

## From the Duckett HTML book:
### Chapter 7: “Forms” (p.144-175)

Information from form is sent in name/value pairs.  Information is sent to a server along with a name.

```HTML
<form action="URL the will receive information" method="either get or post">
```
```HTML
<input type="text" name="the form control name being sent" />

<textarea name="the form control name" cols="20" rows="4">text here</textarea>

<input type="radio" name="same control name" value="value attribute to be sent to the server" />

<input type="checkbox" name="same" value="same" checked="checked" />

<select name="same">
    <option value="same">Text for option 1</option>
    <option value="same">Text for option 2</option>
</select>

<select name="same" size="Number of options to choose at once" multiple="multiple">
    <option value="same">Text for option 1</option>
    <option value="same">Text for option 2</option>
</select>

<input type="file" name="same" />

<input type="submit" name="same" value="same" />

<input type="image" src="path to image to be used as button" width="" height="" />

<input type="date" name="depart" />

<input type="email" name="email" />

<input type="search" name="search" />
```

### Chapter 14: “Lists, Tables & Forms” (pp.330-357)

* List specific
- list-style-type
- list-style-image
- list-style-position
- list-style  (shorthand list style letting you specify type, image, position)
* Table specific
- empty-cells 
- border-spacing
- border-collapse
- cursor

## From the Duckett JS book:
### Chapter 6: “Events” (pp.243-292)

* Interactions Create Events
* Events Trigger Code
* Code Responds to Users

Event Types:
- UI Events
- Keyboard Events
- Mouse Events

How event trigger JS code:
- Select element node(s) to respond to
- indicate event on seleceted nodes will trigger response (called binding)
- State Code to run when event occurs

