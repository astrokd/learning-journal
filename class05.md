# Class 05

301 is all paired programing

-HW: 
    - CSS Selector
    - Behavioral Questions
    - Partner Power Hour

Deploy app on github: make a git pages site

Never make changes on master branch going forward

Create a branch and check it out at the same time
`git checkout -b first-branch`

first-branch is the new branch name
`git push origin first-branch`

On github you can review the changes an pull into master.

Make each change on different branch
> branches are free

function expressions vs function declaration

**expression**  (not hoisted, can only be called after)
``` Javascript
var cat = function() {
    console.log('Meow');
}
```

**declaration**  (hoisted to top, can be called anywhere)
``` Javascript
function dog() {
    console.log('Woof');
}
```

Changing or adding values to Arrays

``` Javascript
var pets = ['munchkin', 'biscuit', 'honey', 'joy', 'bad dog'];

pets.push('mangosteen');

var poppedIndex = pets.pop(); // remove last item of array

pets.shift(); // removes first array

pets.unshift('bob'); // adds to front of array

console.log(pets.indexOf('biscuit')); // finds array index for specified value

pets.splice(1,0,'fish' 'pea'); // delete and/or add array item
// .splice(starting index, delete count, items to add)
```

**Functions**
Anything after the return statement will not run

with bracket notation you can return arrays out of a function

``` Javascript
function sum(a, b) { //eslint-disable-line
  var addSum = a + b;
  var answer = 'The sum of ' + a + ' and ' + b + ' is ' + addSum + '.';
  return[addSum, answer];
}
```

**Shortcut**
- VS Code
 - `option Z`  Toggle Word Wrap


1. Fork the 201d53 repo on GitHub
2. Clone (git clone <forkedrepo>) the repo to your machine and open in vscode
3. Checkout (git checkout -b <problem#>)to a new branch, then start working.
4. Complete the first question
5. A C P to your repo (add, commit, git push origin <problem#>)
6. Merge (on github or git merge <problem#>)your branch into your master on Github
7. On your machine switch to master (git checkout master) and then do a -git pull origin master-,  so that your machine has the updated changes.  
8. Checkout to a new branch git checkout -b <problem#> and complete the next problem, then continue repeating this process until you’re done.
9. After you’ve completed all the questions, make a pull request to the 201d53 repo, grab that URL and submit it in Canvas as your submission.

[Readme learning journal](README.md)