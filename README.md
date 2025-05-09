# Simple Piano

A Flutter-based piano application that provides a simple and interactive way to play piano notes. This project demonstrates the implementation of a basic piano interface with audio playback functionality.

## Features

- Interactive piano keys with touch/click support
- Real-time audio feedback using audioplayers package
- Clean and minimalist user interface
- Cross-platform support (iOS, Android, Web)
- Five distinct piano keys with unique sounds

## Prerequisites

Before running this application, make sure you have the following installed:

- Flutter SDK (>=2.18.1 <3.0.0)
- Dart SDK
- Android Studio / VS Code with Flutter extension
- iOS development setup (for iOS deployment)

## Getting Started

1. Clone the repository:
```bash
git clone [repository-url]
cd simple_piano
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the application:
```bash
flutter run
```

## Project Structure

```
simple_piano/
├── lib/
│   └── main.dart          # Main application code
├── assets/               # Piano sound files
│   ├── key01.mp3
│   ├── key02.mp3
│   ├── key03.mp3
│   ├── key04.mp3
│   └── key05.mp3
└── pubspec.yaml          # Project configuration
```

## Dependencies

- `flutter`: SDK
- `audioplayers: ^1.2.0`: For playing audio files
- `cupertino_icons: ^1.0.2`: iOS style icons

## Usage

The app presents a simple interface with five piano keys. Each key represents a different note:

- D (Key 1)
- R (Key 2)
- M (Key 3)
- F (Key 4)
- S (Key 5)

Simply tap or click on any key to play its corresponding note.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
