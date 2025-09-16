# Flutter Quiz App 🎯

A beautiful and interactive Flutter quiz application designed to help users learn Flutter concepts through an engaging question-and-answer format. The app features a modern gradient UI, question shuffling, and detailed results tracking.

## Features ✨

- **Interactive Quiz Interface**: Clean and intuitive user interface with gradient background
- **Question Shuffling**: Answer options are randomly shuffled for each question to enhance learning
- **Progress Tracking**: Real-time progress through the quiz questions
- **Detailed Results**: Comprehensive results screen showing correct answers and performance summary
- **Restart Functionality**: Ability to restart the quiz and take it multiple times
- **Responsive Design**: Optimized for various screen sizes and orientations
- **Modern UI**: Beautiful gradient backgrounds and Material Design components

## Tech Stack / Technologies Used 🛠️

- **Flutter**: Cross-platform mobile development framework
- **Dart**: Programming language for Flutter development
- **Material Design**: UI design system for consistent and beautiful interfaces
- **State Management**: Flutter's built-in StatefulWidget for managing app state
- **Asset Management**: Image assets and custom styling

### Dependencies

- `flutter`: ^3.8.0 (SDK)
- `cupertino_icons`: ^1.0.8 (iOS-style icons)
- `flutter_lints`: ^5.0.0 (Code quality and linting)

## Installation Instructions 📱

### Prerequisites

Make sure you have the following installed on your system:

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (version 3.8.0 or higher)
- [Dart SDK](https://dart.dev/get-dart) (comes with Flutter)
- [Android Studio](https://developer.android.com/studio) or [VS Code](https://code.visualstudio.com/) with Flutter extensions
- An Android device/emulator or iOS simulator

### Setup Steps

1. **Clone the repository**

   ```bash
   git clone <your-repository-url>
   cd first_one
   ```

2. **Install dependencies**

   ```bash
   flutter pub get
   ```

3. **Verify Flutter installation**

   ```bash
   flutter doctor
   ```

4. **Run the application**
   ```bash
   flutter run
   ```

## Usage 🚀

### Running the App

1. **Start the app**: Launch the application using `flutter run`
2. **Select device**: Choose your target device (emulator, simulator, or physical device)
3. **Begin quiz**: Tap the "Start Quiz" button on the welcome screen
4. **Answer questions**: Select your answer for each Flutter-related question
5. **View results**: After completing all questions, review your score and detailed results
6. **Restart**: Use the "Restart Quiz" button to take the quiz again

### App Flow

```
Welcome Screen → Questions Screen → Results Screen
     ↑                                    ↓
     ←←←←←←← Restart Quiz ←←←←←←←←←←←←←←←←←←←
```

### Example Questions

The quiz includes questions about:

- Flutter UI building blocks (Widgets)
- StatefulWidget vs StatelessWidget
- State management in Flutter
- UI update mechanisms

## Project Structure 📁

```
lib/
├── main.dart                 # App entry point
├── quiz.dart                 # Main quiz widget with state management
├── start_screen.dart         # Welcome screen with start button
├── questions_screen.dart     # Question display and navigation
├── results_screen.dart       # Results display and restart functionality
├── questions_summary.dart    # Detailed question-by-question results
├── answer_button.dart        # Custom answer button widget
├── data/
│   └── questions.dart        # Quiz questions and answers data
└── models/
    └── quiz_question.dart    # Quiz question data model

assets/
└── images/
    └── quizz.png            # Quiz app logo/icon

android/                      # Android platform-specific files
ios/                          # iOS platform-specific files
web/                          # Web platform-specific files
windows/                      # Windows platform-specific files
macos/                        # macOS platform-specific files
linux/                        # Linux platform-specific files
```

### Key Files Explanation

- **`main.dart`**: Application entry point that initializes the Quiz widget
- **`quiz.dart`**: Core widget managing the entire app state and screen navigation
- **`start_screen.dart`**: Welcome screen with app branding and start button
- **`questions_screen.dart`**: Handles question display, answer selection, and navigation
- **`results_screen.dart`**: Shows final score, detailed results, and restart option
- **`data/questions.dart`**: Contains all quiz questions and their answer options
- **`models/quiz_question.dart`**: Data model defining the structure of quiz questions

---

