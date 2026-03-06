# Grade Calculator & Flutter GradeGenie

A comprehensive repository containing applications and exercises focused on automated student grading and logic implementation. This repository includes both a mobile application (GradeGenie) and command-line utilities.

## Contributors

- **Amagna Tcounkeu Robbert Mael** 
- **Kam Kamdem Nathanaël**

## Course Overview

This repository serves as a collection of practical assignments and exercises completed during the application development process. It showcases the progression from fundamental Dart concepts to advanced Flutter application development practices, specifically focusing on data processing and UI automation.

## Repository Structure

```text
Grade-Calculator/
├── Class-Excersie-Dart-Version/
│   ├── grade_calculator_app/    # GradeGenie - Flutter Mobile Application
│   │   └── grades/              # Main Flutter project directory
│   └── grade_calculator_console/# Dart Command-line utility
├── CA-Project/                  # Course assignment projects
│   └── LearnWise-App/           # Integrated learning platform (Placeholder)
└── README.md                    # This file
```

## Technologies Used

- **Language**: Dart
- **Framework**: Flutter
- **Platform**: Android / Web / Desktop
- **Main Dependencies**:
  - `excel`: For reading and writing grading sheets.
  - `file_picker`: For selecting Excel files.
  - `share_plus`: For sharing results.
  - `google_fonts`: For enhanced typography.
- **Build System**: Gradle

## What's Included

### GradeGenie (Flutter App)

A robust mobile application designed to automate the grading process for educators.

- **Excel Integration**: Upload student score sheets in `.xlsx` or `.csv` format.
- **Automated Calculation**: Instantly computes grades based on predefined rubrics.
- **Result Export**: Generate and share updated Excel sheets with finalized grades.
- **Modern UI**: Clean, responsive design using `google_fonts` and Material Design.

### Grade Calculator Console

A lightweight Dart console application for quick terminal-based grade calculations.

- Demonstrates core business logic without UI overhead.
- Useful for testing grading algorithms and batch processing.

### Exercises & Assignments

Foundational coding drills covering:

- Dart Classes and Objects
- Lambda Functions and Higher-Order Functions
- Data Persistence and File Handling
- Asynchronous Programming

## Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (latest version)
- Dart SDK
- Android Studio or VS Code with Flutter extensions

### Installation

1. Clone the repository:

   ```bash
   git clone [https://github.com/Mael-14/Android-App-Development.git]
   cd Android-App-Development
   ```

2. Navigate to the app directory:

   ```bash
   cd Class-Excersie-Dart-Version/grade_calculator_app/grades
   ```

3. Get dependencies:

   ```bash
   flutter pub get
   ```

### Running the Apps

- **Flutter App**:

  ```bash
  flutter run
  ```

- **Console App**:

  ```bash
  dart run Class-Excersie-Dart-Version/grade_calculator_console/main.dart
  ```

## Learning Outcomes

- Understanding Flutter's application lifecycle.
- Managing State and UI components in Flutter.
- Implementing data persistence via `path_provider`.
- Integrating external file formats (Excel) into mobile workflows.
- Following best practices in Dart programming (Lambdas, HOFs, Classes).

## License

This project is provided as educational material. Usage is restricted to course participants and is intended for learning purposes only.

---
**Last Updated**: March 2026
**Repository URL**: [https://github.com/Mael-14/Android-App-Development]
