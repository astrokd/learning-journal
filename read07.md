Article:
[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

## From the Duckett HTML book:
Chapter 6: “Tables” (pp.126-145)

## From the Duckett JS Book:

Chapter 3: “Functions, Methods, and Objects” (pp.106-144)

### Create an Object: Constructor Notation
Using the `new` keyword and the `Object` constructor you can create new objects.

``` Javascript
var hotel = new Object();

hotel.name = 'Quay';
hotel.rooms = 40;
hotel.booked = 25;
hotel.checkAvailability = function() {
    return this.rooms - this.booked;
}
```

Adding properties
`hotel.gym = false;`
Deleting properties
`delete hotel.booked;`

You can create objects then add properties or methods

Literal Notation
```Javascript
var hotel = {}

hotel.name = 'Quay';
```
Object Constructor Notation
```Javascript
var hotel = new Object();

hotel.name = 'Quay';
```
You can create Objects with Properties & Methods

Literal Notation
```Javascript
var hotel = {
    name: 'Quay',
    rooms: 40,
    booked: 25
};
```

