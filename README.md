PROJECT STRUCTURE:-
SurfaceAreaCalculator/
├── src/
│   ├── shapes/
│   │   ├── Shape.java
│   │   ├── Rectangle.java
│   │   ├── Square.java
│   │   ├── Circle.java
│   │   ├── Triangle.java
│   │   └── Cylinder.java
│   ├── exceptions/
│   │   └── InvalidDimensionException.java
│   ├── utils/
│   │   └── InputValidator.java
│   ├── Main.java
│   └── SurfaceAreaCalculator.java
├── docs/
   └── README.md
# Surface Area Calculator

A Java application that calculates the surface area of various geometric shapes using Object-Oriented Programming principles.

## Features

- Calculates area for 5 shapes:
  - Rectangle
  - Square
  - Circle
  - Triangle
  - Cylinder
- Input validation for all dimensions
- Clean, modular code following OOP principles
- Comprehensive error handling

## How to Use

1. Run the program
2. Select a shape from the menu
3. Enter the required dimensions when prompted
4. View the calculated area
5. Choose another shape or exit the program

## Technical Details

- **Programming Paradigm**: Object-Oriented Programming
- **Design Patterns**: Factory pattern (shape creation)
- **Exception Handling**: Custom InvalidDimensionException
- **Input Validation**: Separate InputValidator utility class

## Requirements

- Java 8 or higher
