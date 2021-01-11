# JavaScript Chaat Sheet

## include JavaScipt
To include JavaScript inside a page, you need to wrap it in `<script>` tags:
```
<script type="text/javascript">
//JS code goes here
</script>
```
We can also execute the code of another file from the following menu:

`<script src="myscript.js"></script><code></code>`

## Include comments
To comment we use the following:

`/ this is a comment /`

And if we want more than a line we use this:
```
 /* this is 
a comment /* 
```
## Variables

We can declare variables in three different ways:

* `var`: It can be reassigned but only accessed within a function. Variables defined with var move to the top when the code is executed.

* `const`: Can not be reassigned and not accessible before they appear within the code.

* `let`: Similar to const, the let variable can be reassigned but not re-declared.

## Data types

Variables can have different types of data, there are the following:

* Numbers  `var age = 20`
* Variables  `var y`
* Text (strings)  `var a = "init"`
* Operations  `var b = 1 + 2 + 3`
* True or false statements `var c = true`
* Constant numbers `const example1 = 2.12`
* Objects  `var name = {firstName:"Jose", lastName:"Cabrera"}`

## Objects

Objects are variables that can have their own values and methods. The latter are actions that you can perform on objects.

This is a examble of an object:
```
var client1 = {
    firstName:"Jose",
    lastName:"Cabrera",
    age:20,
    nationality:"Spain"
};
```
## JavaScript Blokers

If we write `alert (" ");`  we can show a message that appears as an alert

We can write in the browser console if we put `console.log (" ")`

with console we also have `console.error (" ")` to send an error message

## Blocks-leves

We can create variables that we can modify with `let = number`.

If we want to put a variable that cannot be modified we use `consts = 1;`

## Variable properties

with a sping variable we put `.length ()` to know its length

To see only a few characters of a variable we use `substring (5,8)`. In this case we see from the fifth to the eighth character

## Multiple variables

If we want to create a variable that has several values, first we create an array and then we create an object where we will define several variables

For example:
```
conts person {
   nombre = 'Jose',
   lastName = 'Cabrera',
}
```

Once this is done we can create an array
```
conts f1 = [ 
conts person {firstname = 'jose', lastName = 'Cabrera', },
conts person1 {firstname = 'Sergi', lastName = 'Palou', }
]
```
## FOR

To create loops we use For
example:

for (let step = 0; step < 5; step++) {


## While


We can also do loops with while

```
n = 0;
x = 0;
while (n < 3) {
  n ++;
  x += n;
```
