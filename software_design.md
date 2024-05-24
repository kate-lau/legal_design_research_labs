# Software Design Research

1. What do we mean by **coupling** and **cohesion** when discussing structured design?
> * COUPLING - How interdependent two separate software modules are from one another. N.B. best to keep this level low

> * COHESION - How closely related the different tasks within one module relate to each other. N.B. best to keep this level high

2. What is the difference between **top-down** and **bottom-up** design? Which best describes a function oriented design?
> * TOP DOWN - starts from a bigger-picture design of what a system's functionality should look like, then broken down into smaller components

> * BOTTOM DOWN - starts with the more specific, lower-levels of functions and intergrates/combines them into a wider system

> * Top-down best describes a function-oriented design, as the design process goes overall function > detailed/basic/foundational components needed to carry out that function

3. In which design methodology would a **class diagram** be most useful?
> * Object-Oriented Programming - to show the different classes (objects) and the relationships between them

4. What are the **four pillars of object oriented programming**? Give a single-sentence description of each.
> * ENCAPSULATION - the placing of properties and methods into a single class and restricting access to some private/protected components and controlling data interaction through public methods

> * ABSTRACTION - the process of hiding complex system details and simplifying thy interaction interface as much as possible

> * INHERITANCE - the mechanism by which one subclass can inherit properties and methods from a parent class/superclass

> * POLYMORPHISM - the ability of different classes to be treated as instances of the same class, allowing for methods to be shared using Interfaces

5. What is the **strategy pattern**? How would its implementation differ between a functional and object oriented system?
> * STRATEGY PATTERN - allows a programme to selec an algorithm from a family, which makes them interchangeable and can be switched back and forth without altering the code that uses them

> * Implementation in Functional Systems: express algorithms as functions, intergrating these into other functions that need to use them 

> * Implementation in Object Oriented Systems: define one Interface for all algorithms, defining each algorithm as its own class, using a wider class to execute the algorithm

6. Imagine you are creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.
> * Bottom-up design, because developing the basic payment functions that can be customised for different sectors is more important in this case. 