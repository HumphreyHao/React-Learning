var: can live in the whole function, even in the()
let: can only live in the block
const: can only live in the function

    try to use let/const instead of the var

## Comma Operator:
run each element one by one, and return the last one


In Js, the variables can be inited in this way:
```
const student = {
  ID: '21',
  name: 'Jhon',
  GPA: '3.0',
};
const {name:n} = student;
```
and in this way:
const {ID, name, GPA} = student;

the student when it was called can return all his values in order of the definition

## Spread Operator:
```
a = [1,2,3];
b = [4,5,6];
c = [...a, ...b]; 
```

You can even use spread operator to combine two object:
```
const person = { name: "Jhon"};
const student = { ID: "21", GPA: "3.0"};

const new_object = { ...person, ...student, semester: '3'};
console.log(new_object);
```






