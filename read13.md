# Read 13: Local Storage

[“The Past, Present, and Future of Local Storage for Web Applications”](http://diveinto.html5doctor.com/storage.html)

## The Past
Early in the web Cookies were invented to store small amounts of data.  Cookies have a 4 KB and every page refresh the data is transmited over the internet unencrypted.  This can greatly slow your application, and expose you to hackers.

Before HTML there were a lot of attempts at creating a solution but most were implements in only one browser and requiered a plugin.

## HTML5 Storage
Named Web Storage in the spec but called differently in different browsers.  Currently this is implemented in every major browser.

**HTML5 STORAGE SUPPORT**
IE   |FIREFOX | SAFARI |CHROME |OPERA | IPHONE |ANDROID
8.0+ |3.5+    | 4.0+   |4.0+   |10.5+ | 2.0+   |2.0+

### Using Storage
From JavaScript code you can access this storage from an object called `localStorage`. Data in in localStorage is stored based on named key/value pair.  Datatype stored can be any type but the actual storage is a string.  There are methods called getItem and setItem that let you make and read key/value pairs but you can also use square bracket[] notation the read and write.

The localStorage object is limited to 5MB and an exception is thrown when this is exceed and it is not possible to increase this amount.

## Future
There are competing ideas for improvements to Local Storage.  WebDB and other Database solutions exist and some have support in multiple browsers.