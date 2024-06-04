# Android Calculator App

This is a simple calculator application for Android, built using Kotlin. The app supports basic arithmetic operations including addition, subtraction, multiplication, and division.

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, division.
- Clear (C) button to reset the calculator.
- Support for decimal numbers.
- Different layouts for portrait and landscape modes.

## Installation

To get a local copy up and running follow these simple steps.

### Prerequisites

- Android Studio installed on your machine.
- Android SDK setup.

### Clone the Repository

```bash
git clone https://github.com/yourusername/android-calculator.git
```

In the Android Studio, open the project from the cloned repository.

### Build and Run

- Build and run the project on an Android emulator or a physical device.
- Select Open an existing Android Studio project.
- Navigate to the project directory and select the android-calculator folder.
- Let Android Studio import the project and download any necessary dependencies.


### Usage

- Open the app on an Android device or emulator.
- Use the calculator buttons to perform arithmetic operations.
- Press the C button to clear the calculator.
- The = button evaluates the expression and displays the result.


## Project Structure

The project is structured as follows:


```bash
android-calculator/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/calculator/
│   │   │   │   ├── MainActivity.kt
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   ├── activity_main.xml
│   │   │   │   ├── layout-land/
│   │   │   │   │   ├── activity_main.xml
│   │   │   │   ├── values/
│   │   │   │   │   ├── styles.xml
│   │   ├── AndroidManifest.xml
├── build.gradle
├── README.md

```

