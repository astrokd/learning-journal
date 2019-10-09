# Monday Oct 7th Class 6

CSS

Position: absolute; takes elements out of the main flow of a page

## Objects
``` Javascript
var person = {
  name: 'Grace Hopperr',
  age: 85,
  computerScientist: true,
  education: ['Vassar College','Yale University'],
  walk: function() {
    console.log('I am walking...');
  }
}

person.serviceBranch = 'Navy';
person.myObj = {1: 'stuff', 2: 'other stuff'};

console.log(person);
```

The contectual This

`this` is referring to the object that is being manipulated or accessed

`this` references the current object

Template Literials
instead of 'test ' + array[i];
use back tick ``test ${array[i]}``

### Git Branching steps
1. `git checkout -b (branchName)`
2. Code branch changes
3. ACP
    1. `git push origin (branchName)`
4. Merge branch into master on GitHub
5. Switch to master locally, `git checkout master`
6. `Git pull origin master` to get the changes from merge locally on master
7. repeat for a new set of changes

[Readme learning journal root](README.md)