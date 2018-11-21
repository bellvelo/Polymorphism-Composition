Polymorphism

What does the word 'polymorphism' mean?
 - From the greek, many shapes/forms.

What does it mean when we apply polymorphism to OO design? Give a simple Java example.
 - it means we can wrap objects up in an enclosing type that defines a contract between them all. So if we have an interface with a 'buy' method. All classes that implement it have to use that 'buy' method.

What can we use to implement polymorphism in Java?
- Abstract Classes and Interfaces can be used to implement polymorphism. When a class implements an interface, it gains the type of the interface. Also classes can have many interfaces.

How many 'forms' can an object take when using polymorphism?
- many.

Give an example of when you could use polymorphism.
- ArrayLists are an example of Polymorphism (parametric polymorphism), as we can pass multiple types of class into it.(wrapped in an interface).


Composition

What do we mean by 'composition' in reference to object-oriented programming?
- Passing one class into another, along with any methods it has.

When would you use composition? Provide a simple example in Java.
- You would have an instance of a class within another class. If you had a 'Computer class', you would include, along with the Computers variables, another Class, say 'private Monitor monitor' which would then go into the 'Computer' constructor. Composition would be used in a 'has a' scenario. As in a computer has a monitor.

What is/are the advantage(s) of using composition?
- Flexible and maintainable code, which is easily scalable. Good for ensuring classes have single responsibility.
