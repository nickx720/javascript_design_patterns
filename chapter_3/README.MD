# Encapsulation and Information Hiding

**What is Encapsulation?**

Encapsulation is the hiding of internal data representation and implementation details in an object.

---

**What role does interface provide in encapsulation?**

It defines the relationship that two objects can have, either object in this relationship can be replaced as long as the interface in maintained. Ideal software system has interface for all classes. Classes only provide the methods defineds in their interfaces, every other method is private.

---

**What is an accessor method?**

Gets the value of any attributes.

---

**What is a mutator method?**

Sets the value of any attributes.

---

**Does the use of _ in variable name signify they are meant to be private?**

Yes

---

**What are privileged methods?**

Methods that have access to private variables.

---

**What is the advantage of static members over other private/privileged function with access?**

They are only stored in the memory once.

---

**What are the benefits of Encapsulation?**

1. Protects integrity of the internal data.
2. Access is only via accessor and mutator methods.
3. Allows easy replacement of internal logic.
4. Loosely coupled modules.

---

**What are the drawbacks of using Encapsulation?**

1. Very hard to unit test private methods because they are hidden.
2. Hard to debug.
