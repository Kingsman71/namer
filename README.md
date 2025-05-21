# Namer App

 A simple Flutter app that suggests random English word pairs and lets users favorite the ones they like. Built using `provider` for state management and supports responsive layouts.

## Features

* Generates random English word pairs using the `english_words` package.
* Users can:

  * Tap "Like" to favorite a word pair.
  * Tap "Next" to generate a new word pair.
* Favorites are displayed in a separate view.
* Responsive design using `NavigationRail` for larger screens.

## Built With

* Flutter
* Dart
* [english\_words](https://pub.dev/packages/english_words)
* [provider](https://pub.dev/packages/provider)

## Getting Started

### Prerequisites

* [Flutter](https://flutter.dev/docs/get-started/install) installed on your machine

### Run the App

```bash
flutter pub get
flutter run
```

## Deployment

```bash
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/Kingsman71/namer.git
git branch -M main
git push -u origin main
```

## License

This project is licensed under the MIT License.

---

Made with ❤️ using Flutter.
