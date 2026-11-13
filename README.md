# Quiz Application – Interactive Quiz App

A modern, user-friendly mobile application developed using **Flutter** and **Dart**. Quiz Application helps students test their knowledge through multiple-choice questions, explore different categories, track scores, view results, and add their own custom questions.

## 📱 Quiz Application Screenshots

*Screenshots will be added after completing the application.*

- Home Screen
- Quiz Categories Screen
- Quiz Questions Screen
- Results Screen
- Add Questions Screen

---

## 📲 Download Android App

The release APK will be available after completing the application.

- **GitHub Release:** Quiz Application v1.0.0
- **Repository:** Quiz-Application

---

## 📌 Features

- **Quiz Categories:** Browse General Knowledge, Science, Computer Science, Mathematics, and English.
- **Start Quiz:** Select a category and start a quiz.
- **Multiple-Choice Questions:** Answer questions with four options.
- **Score Tracking:** Calculate scores based on correct answers.
- **Question Progress:** Display question numbers and progress.
- **Results Screen:** View total score, correct answers, incorrect answers, and percentage.
- **Add Custom Questions:** Create questions with four options and select the correct answer.
- **Category Details:** View category information.
- **Best Score:** Save and display the highest score.
- **Local Storage:** Save custom questions and best scores on the device.
- **Loading & Error Handling:** Handle loading, errors, and retry options.
- **Form Validation:** Validate question text and answer options.

---

## 🏗️ Project Architecture

```text
lib/
├── main.dart
├── models/
│   ├── question.dart
│   └── category.dart
├── services/
│   ├── quiz_provider.dart
│   └── storage_service.dart
├── screens/
│   ├── home_screen.dart
│   ├── category_detail_screen.dart
│   ├── quiz_screen.dart
│   ├── result_screen.dart
│   └── add_question_screen.dart
└── widgets/
    ├── category_card.dart
    ├── question_card.dart
    └── option_button.dart
```

---

## 👥 Team Contributions

| Team Member | Responsibilities |
|---|---|
| **SK Mukharamsha** | Home Screen, Quiz Categories, Category Details, Project Setup and Navigation |
| **Y Ranjitha** | Quiz Screen, Multiple-Choice Questions, Score Calculation and GitHub Setup |
| **V Chandrika** | Results Screen, Add Custom Questions, Form Validation and Testing |

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (v3.35 or higher)
- Dart SDK
- Antigravity or VS Code
- Android device or emulator

### Installation & Run

1. Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Open the project folder:

```bash
cd Quiz-Application
```

3. Install dependencies:

```bash
flutter pub get
```

4. Run the application:

```bash
flutter run
```

---

## 🧪 Testing

The application will be tested for:

- Quiz category loading.
- Starting and completing a quiz.
- Score calculation.
- Adding custom questions.
- Form validation.
- Saving and retrieving best scores.
- Screen navigation.

Run tests using:

```bash
flutter test
```

---

## 📦 Build Release APK

```bash
flutter build apk --release
```

APK output:

```text
build/app/outputs/flutter-apk/app-release.apk
```

---

## 🛠️ Technologies Used

- **Flutter** – Mobile application development
- **Dart** – Programming language
- **Provider** – State management
- **SharedPreferences** – Local data storage
- **REST API** – Online quiz questions (if implemented)
- **Git & GitHub** – Version control and collaboration

---

## 👩‍💻 Developed By

**Team Quiz Application**

1. SK Mukharamsha
2. Y Ranjitha
3. V Chandrika

**Version:** 1.0.0+1

**Tag:** v1.0.0

**Language:** Dart + Flutter
