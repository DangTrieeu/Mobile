Name: Lý Đăng Triều

StudentID: 22110080

## Overview

This project is a component of Google's Advanced Android Testing course, showcasing best practices for testing Android applications. It features unit tests, instrumentation tests, and UI tests, utilizing JUnit, Mockito, and Espresso.

## TasksViewModelTest.kt

The `TasksViewModelTest.kt` file contains unit tests for the `TasksViewModel` class, ensuring the ViewModel behaves correctly under different scenarios.

### Key Features:
- Uses JUnit and Mockito for unit testing.
- Tests ViewModel logic without requiring an actual UI or database.
- Verifies LiveData updates correctly.
- Mocks repository dependencies to isolate ViewModel behavior.

## Technologies Used
- **Kotlin** for programming language.
- **Android ViewModel** for UI-related data management.
- **LiveData** for observable data streams.
- **JUnit** for unit testing.
- **Mockito** for mocking dependencies.
- **Espresso** for UI testing.

## Running the Tests
To execute the tests:
1. Open the project in Android Studio.
2. You need to build this project in JDK version 11 by navigating to **Files -> Settings -> Build, Execution, Deployment -> Build Tools -> Gradle**, then download or use JDK version 11 if you have it.
3. Navigate to `TasksViewModelTest.kt` or `StatisticsUtilsTest.kt`.
4. Select any function you want to test.
