# Classes and Objects

A example
```
class Developer {
  constructor(firstname, lastname) {
    this.firstname = firstname;
    this.lastname = lastname;
  }
```

create an object is very similar with a class

eg:
```
let computer3 = {
  brand : 'HP',
  RAM : '8 GB',
  clockspeed : "2 GHz",
  
  printRam() {
    console.log(this.RAM)
  }
```

Explicit Binding;
need use the call to bind this function with the object

or we can use apply to bind and pass the input in it

or we can use bind() function to return a new function
eg:
```
// Here we bind the me object to the printName() function and get a new function called newPrintName()
const newPrintName = printName.bind(me);
```

### Composition
classes containing instances of other classes as attributes to implement the desired functionality, instead of  inheriting classes

