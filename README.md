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

---

## Topics Covered

**Dart Programming**
- String methods: replaceAll, split, substring, contains, toString
- Collections: List, Set, Map operations
- Functions: return types, parameters, void functions

**Object-Oriented Programming (OOP)**
- Inheritance using `extends`
- Method overriding with `@override`
- Abstract classes
- Interface implementation using `implements`
- Polymorphism

**Flutter UI Development**
- MaterialApp, Scaffold, AppBar setup
- Layout widgets: Column, Row, SizedBox
- Text widget with custom styles (color, fontSize, fontWeight, fontStyle, letterSpacing)
- Icon and IconButton widgets
- Buttons: ElevatedButton, TextButton, OutlinedButton, IconButton
- Image loading from network using Image.network
- mainAxisAlignment and crossAxisAlignment
- Nested layouts (Row inside Column, Column inside Row)

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

> Note: Each `.txt` file may contain multiple separate code examples. Copy one example at a time into `main.dart`.

---

## Author

Kazi Arafat Hossain
