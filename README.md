# Multi-Function Android Calculator

A modern, reactive Android calculator built with **Jetpack Compose** and **Kotlin**. This project demonstrates a clean implementation of the **MVVM architecture** and state management using **StateFlow**.

<img src="https://github.com/user-attachments/assets/b5ceb1ec-9234-4813-802b-dfd8b820d3a3" width="300"/>  <img src="https://github.com/user-attachments/assets/bb81857d-c7b5-4500-b03d-9f192d8853f7" width="300" />


## 🚀 Features

* **Advanced Math Support**: Includes support for Square Root (√), Pi (π), Power (^), Factorials (!), and Percentages (%).
* **Intelligent Parentheses**: Custom logic to automatically determine whether to insert an opening or closing parenthesis based on the current expression.
* **Real-time Evaluation**: Provides live calculation results as the user types.
* **Dynamic Theming**: Supports both **Dark** and **Light** modes with Material 3 color schemes.
* **Modern UI**: Utilizes a declarative Compose UI with circular buttons and a custom-shaped display header.

## 🛠 Tech Stack

* **Language**: Kotlin.
* **UI Framework**: Jetpack Compose (Material 3).
* **Architecture**: MVVM (Model-View-ViewModel).
* **State Management**: Kotlin Coroutines & StateFlow.
* **Math Engine**: [mXparser](https://mathparser.org/) for robust expression evaluation.
