# Chapter 4

**Why do you need inheritance?**

1. Reduce the amount of duplicate code.
2. Making your objects as loosely coupled as possible.

---

**How does classical inheritance look in JavaScript?**

`
function Person(name){
this.name = name;
}

Person.prototype.getName = function(){
return this.name;
}
`

---

**Give an example of inheritance using Class in JavaScript?**

`
function Author(name,books){
Person.call(this,name); // Call the superclass's constructor in scope of this
this.books = books; // Add an attribute to Anchor
}

Author.prototype = new Person(); // Set up the prototype chain.
Author.prototype.constructor = Author; // Set the constructor attribute to Author.
Author.prototype.getBooks = function() { // Add a method to Author.
return this.books;
}
`

---

**How do you setup a prototype chain?**

The constructor function is called on an empty object at the front of the scope chain.Once created, set the subclass prototype to point to an instance of the superclass.

For example
`
Author.prototype = new Person(); // Set up the prototype chain.
Author.prototype.constructor = Author; // Set the constructor attribute to Author.
`

---

**What does the this in each constructor function refer to?**

It refers to the empty object at the time of creation.

---

**What is the extend function?**

It is a helper function to make class declaration more simple.

---

**What is Prototypical inheritance?**

Instead of defining the structure through a class as above, create an object, which is reused by new objects.

---

**Give an example of Prototypical inheritance?**

`
var Person = {
name: 'default name',
getName: function(){
return this.name;
}
};
`

---

**What is a prototype object?**

An object literal as above, which can be used for other Person-like objects for Person instance creation.

---
