the [] means a list
the {} means a object

## Important Function
```
    var changeName = setTimeout(function(){
      this.setState({lastname: 'Hood'}); 
    }.bind(this), 5000);
```
which callback the function after the timeInMS milliseconds

the bind function is also vey important，because in this function "this" is the function, so it should be bind with the class
