# Chapter 5

**What is a singleton?**

It provides away to group code into a logical unit that can be accessed through a single variable.

---

**What are the uses of Singleton in JavaScript?**

1. Namespacing
2. Branching (encapsulate browser differences)

---

**What is the basic structure of the Singleton?**

```
var Singleton = {
attribute: true,
method: function(){
...
}
}
```

---

**What is namespacing?**

It ensures that objects are do not pollute the global environment

---

**Give an example of namespace?**

```
var MyNamespace = {
findProduct: function(id){
...
},
}
```

---

**Where can singleton object can be used?**

It can be used to wrap page-specific code.

---

**How do we have private variables in Singleton?**

1. Underscore notation
2. Closures.

---

**What is lazy loading used for with Singleton?**

If a singleton is too expensive to load, it makes sense to defer the instatiation till it is needed and can be done using flags.

---

**What is branching?**

It allows to encapsulate browser differences into dynamic methods that can be set at runtime.

---

**When should the Singleton pattern be used?**

1. Namespacing
2. Modularising

---

**What are the benefits of Singleton pattern?**

1. Organization of code
2. Grouping of related method/attributes together in a single location.

---

**What are the drawbacks of Singleton pattern?**

1. Tightly couples the code
