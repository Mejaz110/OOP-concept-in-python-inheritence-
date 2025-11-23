# OOP-concept-in-python-inheritence-
in this file we learn about oop concept( inheritence) in python language
. Single Inheritance

Single inheritance means one child class inherits from one parent class.

Example:
class Parent:
    pass

class Child(Parent):
    pass

Easy Explanation:

A single child gets features from one parent only.

Simple and easy to understand.

Most common type of inheritance.

2. Multiple Inheritance

Multiple inheritance means one child class inherits from two or more parent classes.

Example:
class Parent1:
    pass

class Parent2:
    pass

class Child(Parent1, Parent2):
    pass

Easy Explanation:

A child gets features from more than one parent.

Powerful but can cause confusion if parents have same method names (called ambiguity).

Python handles this using Method Resolution Order (MRO).
