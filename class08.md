### Shortcut
fn arrow left or right
option arrow left or right


DRY principal => Don't Repeat Yourself

### Code Demo
```Javascript
//array of hours
//array for all stores
//link to html
//all stores total
CookieShop.hours = ['6am','7am','8am']
CookieShop.allStores = [];
//constructor
function CookieShop(min, max, avg, loc) {
    this.min = min;
    this.max = max;
    this.avg = avg;
    this.loc = loc;
    this.hourlyCookiesTotal = [];
    this.dailyCookies = 0;
    CookieShop.allStores.push(this);
    // this.generateHourlyCookie();
    // this.renderShopRow();
}

var chicago = new CookieShop(48, 115, 2.2, Chicago');

CookieShop.prototype.generateHourlyCookie = function() {
    for (var i = 0; i < CookieSHop.hours.length; i++) {

    }
}

var trEl = document.createElement('tr');
```
Forms
best practice /required in forms

everything is an object in javascript
JS is weakly typed language
```html
<form is="user-form">
<fieldset> 
    <label></label>
    <input>
    <label>
    <input>
</fieldset>
```
Event handlers

```Javascript
var userForm = document.getElementById('user-form');
userForm.addEventListner('submit', handleSubmit);

function handleSubmit(event) {
    event.preventDefault();
    console.log('hello from handleSubmit');
};
```
[Readme learning journal root](README.md)