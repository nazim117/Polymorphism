# Polymorphism

# 1. MathOperation
Create a class MathOperations, which should have 3 times method Add(). Method Add() has to be invoked with:
 Add(int, int): int
 Add(double, double, double): double
 Add(decimal, decimal, decimal): decimal

# 2. Animals
Create a class Animal, which holds two fields:
 name: string
 favouriteFood: string
An animal has one virtual method ExplainSelf(): string.
You should add two new classes - Cat and Dog. Override the ExplainSelf() method by adding concrete animal 
sound on a new line.

# 3. Shapes
Create a class hierarchy, starting with abstract class Shape:
 Abstract methods:
o CalculatePerimeter(): double
o CalculateArea(): double
 Virtual methods:
o Draw(): string
 The method should get the name of class type as string, and should 
return a message in the format: $"Drawing {classType.Name}"
Extend the Shape class with two children:
 Rectangle
 Circle
Each of them needs to have: 
 Fields: 
o height and width for Rectangle
o radius for Circle
 Encapsulation for these fields
 A public constructor 
 Concrete methods for calculations (perimeter and area)
 Override methods for drawing 
