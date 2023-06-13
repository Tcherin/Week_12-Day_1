# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

Polymorphism means 'many forms'.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

If a wallet class contained several different types of card class, such as credit or debit cards, and were unnecessarily defining common attributes in each of these classes, rather than using a common card class.

3. What can we use to implement polymorphism in Java?

We can use abstract classes to ensure that any common properties between subclasses are passed down rather having to be redefined over and over.

4. How many 'forms' can an object take when using polymorphism?

As many as is needed.

5. Give an example of when you could use polymorphism.

when many classes could be extended from an abstract class.



# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

When properties and behaviours are wrapped into a single unit.

7. When would you use composition? Provide a simple example in Java.

If you were creating a human class, you would need to also create classes for the main organs of the body.

8. Give a difference between composition and aggregation?

Composition implies ownership, whereas aggregation is more a 'has a' relationship between classes and subclasses.

9. What is/are the advantage(s) of using composition/aggregation?

Allows the model to scale better as its objects have been thought out in far more detail.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?

All component classes are destroyed with the object, as they cannot exist without the other.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

The component classes are able to be removed and used independently.