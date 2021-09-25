# Chapter 2

**What is an Interface?**
An interface provides a way of specifying what methods an object should have. It does _not_ specify how those methods should be implemented.

---

**What are the benefits of using Interfaces?**
1. Reusability
2. Documented
3. Tells what methods are provided by the classes.
4. Stabilizes ways in which different classes communicate.

---

**What are the drawbacks of using Interfaces?**
1. Reduces flexibility
2. Performance takes a hit.
3. Since there is no compiler, no ways to enforce other programmers to respect Interfaces.

---

**What is duck typing?**
It is a technique to determine whether an object is an instance of a class based soley on what methods it implements.
It also checks whether a class implements an interface.

---

**When to use Interfaces?**
In large projects, they are essential especially when the API hasn't been written.
When interacting with external libraries, Interfaces provide a contract so changes with external libraries don't cause errors in your code.

---

**What are the patterns that rely on Interface?**
1. _The factory pattern_ : Objects created by the factory pattern can change based on situation, hence interfaces are used as guarantees.
2. _The composite pattern_ : Composite is a group of objects that can be treated the same as constituent objects.It is accomplished using Interfaces.
3. _The decorator pattern_: Interfaces are used to ensure decorators which are created by wrapping another object, implement needed methods.
4. _The command pattern_ : Command objects (execute,run,undo etc) are implemented using Interfaces so they are modular and loosely coupled.
