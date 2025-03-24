# Simple to do list

Creation of my first basic flutter project.

## Features

✅ Add new tasks

✅ Mark tasks as completed (with a strikethrough effect)

❌ Delete tasks

🎨 Beautiful UI with a Deep Purple theme

## Getting Started

Prerequisites

Ensure you have the following installed on your system:

Flutter SDK

Dart

Android Studio or Visual Studio Code (with Flutter extension)

Installation

Clone the repository:

git clone https://github.com/RohanM007/ToDo-List.git

Navigate to the project directory:

cd ToDo-List-flutter

Install dependencies:

flutter pub get

Run the application:

flutter run

Project Structure

lib/
│── main.dart            # Entry point of the app
│── home_page.dart       # Home screen containing the task list
│── utils/
│   ├── todo_list.dart   # Task item widget
└── README.md            # Project documentation

Code Breakdown

HomePage.dart

Manages the list of tasks.

Handles adding, marking completed, and deleting tasks.

Uses setState to dynamically update the UI.

TodoList.dart

Displays a single task with a checkbox and delete button.

Supports onChanged for marking tasks complete and onDelete for removing tasks.

UI Preview

Task List

Add Task

Delete Task

✅ Learning Flutter

➕ Enter new task

❌ Click the delete icon

✅ Drink Coffee

➕ Tap add button

❌ Removes from lis

