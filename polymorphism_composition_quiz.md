# Polymorphism & Composition Homework - Quiz

Kenny McKeown

# Polymorphism 

1. What does the ___word___ 'polymorphism' mean?
Polymorphism means 'many forms'.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
Polymorphism occurs when classes inherit properties or methods from another class.
   public class ChildClass extends ParentClass - this would be an example.

3. What can we use to implement polymorphism in Java?
    Inheritance or composition.

4. How many 'forms' can an object take when using polymorphism?
2, static and dynamic in the forms of overriding and overloading.

5. Give an example of when you could use polymorphism.
When a child class has a different value for a property defined in the parent class. 
   The child class can override the method or property of the parent.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
composition allows us to build objects by using classes as the building blocks of another class.

7. When would you use composition? Provide a simple example in Java.
Composition can be used when you want a class to take on certain properties but do not want to overload it by using inheritance.
   This means you can be more selective about the properties and methods being shared.

8. What is/are the advantage(s) of using composition?
see answer above.

9. When an object is destroyed, what happens to all the objects it is composed of?
nothing?