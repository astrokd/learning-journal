# JavaScript journal entry
JS provides functionality, like the below JS;
```
    var today = new Date();
    var hourNow = today.getHours();
    var greeting;

    if (hourNow > 18) {
        greeting = 'Good evening!';
    } else if (hourNow > 12) {
        greeting = 'Good afternoon!';
    } else if (hourNow > 0) {
        greeting = 'Good morning!';
    } else {
        greeting = 'Welcome!';
    }

    document.write('<h3>' + greeting + '</h3>');
```
This JS adds text greeting var based on time of day.  The `.getHours()` function finds the time on current os.

JS runs where it is found in the HTML

Inspecting the html in the browser will not show the JS or what the js did