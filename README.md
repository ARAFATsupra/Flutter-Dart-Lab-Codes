# Dart and Flutter Lab Codes

A collection of Dart and Flutter code samples written during lab sessions for the ITM 8th Batch program. This repository covers fundamental Dart programming concepts and Flutter UI development using widgets.

---

## Table of Contents

- [About This Repository](#about-this-repository)
- [File Overview](#file-overview)
- [Topics Covered](#topics-covered)
- [Code Descriptions](#code-descriptions)
- [Requirements](#requirements)
- [How to Run](#how-to-run)
- [Author](#author)

---

## About This Repository

This repository contains hands-on lab exercises written in Dart and Flutter. The codes range from basic Dart programming (strings, lists, maps, functions) to object-oriented programming (OOP) concepts like inheritance, polymorphism, and abstract classes, and finally to Flutter UI layouts using various widgets.

---

## File Overview

| File Name | Category | Description |
|---|---|---|
| `Dart_Codes_1.txt` | Dart Basics | Strings, Lists, Sets, Maps, Functions |
| `Dart_Codes_2.txt` | OOP - Abstract Classes | Abstract class with interface implementation |
| `Dart_Codes_3.txt` | Flutter UI | Basic Column layout with styled Text widgets |
| `Dart_Codes_4.txt` | OOP + Flutter UI | Polymorphism, Interfaces, Column alignments |
| `Dart_Codes_5.txt` | Flutter UI | Rows, Icons, Images, Buttons in a Scaffold |
| `Dart_Codes_Extra.txt` | Flutter UI | Text styles, nested layouts, Row and Column |
| `Dart_Lab_Code.txt` | Flutter UI | Full Flutter layout demo with image, icons, and text |
| `Dart_Extra_Codes_Practice.docx` | Dart + OOP + Flutter | Extended practice notes covering strings, lists, OOP, control flow, functions, mixins, and Flutter UI |

---

## Topics Covered

**Dart Programming**
- String methods: replaceAll, split, substring, contains, toString, toLowerCase, toUpperCase, trim, compareTo
- String concatenation and interpolation
- Collections: List (fixed-length and growable), Set, Map operations
- List methods: add, addAll, insert, insertAll, remove, removeAt, removeLast, removeRange
- Set methods: add, addAll, elementAt, remove, clear
- Map methods: addAll, clear, remove, forEach
- Functions: return types, parameters, void functions, anonymous functions, recursive functions
- Control flow: if, if-else, else-if ladder, switch-case
- Loops: for, for-in, while, do-while

**Object-Oriented Programming (OOP)**
- Classes, objects, and constructors
- Named constructors and factory constructors
- Inheritance: single, multilevel, and hierarchical
- Method overriding with `@override`
- The `super` keyword
- Getters and setters
- Abstract classes
- Interface implementation using `implements`
- Polymorphism
- Mixins for multiple inheritance alternatives
- Composition (has-a relationship)
- Extension methods
- Method overloading alternatives using optional positional, named, and default parameters

**Algorithms**
- Fibonacci series using recursion

**Flutter UI Development**
- MaterialApp, Scaffold, AppBar setup
- Layout widgets: Column, Row, SizedBox, Container
- Text widget with custom styles (color, fontSize, fontWeight, fontStyle, letterSpacing)
- Icon and IconButton widgets
- Buttons: ElevatedButton, TextButton, OutlinedButton, IconButton
- Image loading from network using Image.network
- mainAxisAlignment and crossAxisAlignment
- Nested layouts (Row inside Column, Column inside Row)
- Container with fixed height and width wrapping images
- TabBar and TabBarView for tabbed navigation

---

## Code Descriptions

### Dart_Codes_1.txt - Dart Basics
Covers fundamental Dart operations including string manipulation, list operations (add, addAll, insert, insertAll), Set operations, Map creation, and defining functions with return types.

### Dart_Codes_2.txt - Abstract Classes and Interfaces
Demonstrates how to define an abstract class `Calculator` with method stubs and a concrete body (`fly`), and how class `B` implements all methods of the abstract class.

### Dart_Codes_3.txt - Basic Flutter Column Layout
A simple Flutter app showing multiple styled Text widgets inside a Column with SizedBox spacing. Demonstrates use of AppBar with background and foreground colors.

### Dart_Codes_4.txt - OOP Concepts and Column Alignments
Contains multiple examples: polymorphism using `extends` and `@override`, interface implementation using `implements`, and several Flutter apps showing different `mainAxisAlignment` values (start, end, center, spaceAround, spaceBetween, spaceEvenly) and `crossAxisAlignment`.

### Dart_Codes_5.txt - Flutter Widgets Showcase
A Flutter app with a Scaffold containing rows of text, icons, a network image, and multiple button types (ElevatedButton, TextButton, IconButton) all organized in a Column.

### Dart_Codes_Extra.txt - Text Styles and Nested Layouts
Three separate Flutter apps demonstrating: (1) various Text styling options, (2) a screen combining rows of text, icons, buttons, and images, and (3) a nested layout where a Row contains Columns with icons and labels (Call, Route, Share).

### Dart_Lab_Code.txt - Full Flutter Layout Demo
A complete Flutter UI page simulating a real app layout. Features a full-width network image, location text with a star rating, three action icons (Call, Route, Share) with labels, descriptive paragraph text, and a submit button.

### Dart_Extra_Codes_Practice.docx - Extended Practice Notes
A comprehensive practice document covering a wide range of Dart and Flutter topics with code examples and expected outputs. Topics include:

- String concatenation and interpolation with output examples
- All major string methods with outputs (toLowerCase, toUpperCase, trim, compareTo, replaceAll, split, substring, toString)
- Fixed-length and growable List creation
- All four List insert methods (add, addAll, insert, insertAll) with examples
- All four List remove methods (remove, removeAt, removeLast, removeRange) with examples
- Set initialization and all major Set methods with examples
- Map creation using literal syntax and the Map() constructor
- All major Map methods (addAll, clear, remove, forEach) with examples
- Control flow: if, if-else, else-if ladder, switch-case
- Loops: for loop, for-in loop with list, while loop, do-while loop
- Functions: return types, string-returning functions, void functions with conditionals, anonymous functions using forEach, multiplication function, and recursive factorial
- OOP: class with fields and methods, parameterized constructors, named constructors, this keyword, single inheritance, multilevel inheritance, hierarchical inheritance, super constructor call, method overriding, super keyword usage, getters and setters
- Abstract class and implementation
- Interface implementation using `implements`
- Factory constructors
- Method overloading alternatives: optional positional parameters `[ ]`, optional named parameters `{ }`, default parameter values, dynamic parameters
- Multiple inheritance alternatives: mixin, implements, composition (has-a relationship), extension methods
- Fibonacci series using recursion
- Flutter: Row and Column with Container wrapping Image.network
- Flutter: TabBar and TabBarView for tabbed navigation layout

---

## Requirements

- Flutter SDK (version 3.0 or above recommended)
- Dart SDK (included with Flutter)
- An IDE such as Android Studio or VS Code with the Flutter plugin
- An internet connection (for loading network images in the UI examples)

---

## How to Run

1. Make sure Flutter is installed on your machine. You can check by running `flutter doctor` in your terminal.
2. Create a new Flutter project using `flutter create my_project`.
3. Copy the code from any `.txt` file in this repository.
4. Replace the contents of `lib/main.dart` in your project with the copied code.
5. Run the app using `flutter run` in the terminal, or press the Run button in your IDE.

> Note: Each file may contain multiple separate code examples. Copy one example at a time into `main.dart`. For the `.docx` file, open it and copy individual code blocks as needed.

---

## Author

ITM 8th Batch - Lab Session Codes
Dhaka, Bangladesh
