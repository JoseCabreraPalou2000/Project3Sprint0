# JavaScript Chaat Sheet

## include JavaScipt
To include JavaScript inside a page, you need to wrap it in `<script>` tags:

``<script type="text/javascript">
//JS code goes here
</script>``

We can also execute the code of another file from the following menu:

`<script src="myscript.js"></script><code></code>`

## Include comments
To comment we use the following:

`/ this is a comment /`

And if we want more than a line we use this:

`` /* this is 
a comment /* ``

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

``var client1 = {
    firstName:"Jose",
    lastName:"Cabrera",
    age:20,
    nationality:"Spain"
};``

a lo mejor tengo que hacer las array aqui