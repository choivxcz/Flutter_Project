# Flutter Project (formerly flutter_try)

## Description

This repository contains the practice work of Karl Sebastian V. Cuerdo in learning Flutter and Dart. It includes exercises on layouts, navigation, animation, user authentication, and Firebase integration, together with a small set of Python exercises from class.

The final project developed in this repository, Peso Pilot, has since been moved to its own repository, [Peso-Pilot-App](https://github.com/choivxcz/Peso-Pilot-App), where its current version and setup instructions are maintained. The copy in `lib/final_project/` is retained for reference.

## Repository Structure

```
lib/
  final_project/   Original version of Peso Pilot (retained for reference)
  pages/           Practice screens: welcome, sign-in, profile, navigation, and animations
  widgets/         Reusable practice widgets (navigation bar and drawer)
api/               Serverless proxy used by the Peso Pilot AI chat
functions/         Firebase Cloud Functions version of the same proxy
python-practice/   Python class exercises (loops, lists, and file storage)
```

## Requirements

Flutter SDK with Dart.

## Usage

```bash
flutter pub get
flutter run --dart-define=OPENROUTER_BACKEND_URL=https://your-project.vercel.app/api
```

The AI chat in the final project requires the proxy in `api/` to be deployed with an `OPENROUTER_API_KEY` environment variable. Detailed instructions are provided in the [Peso-Pilot-App documentation](https://github.com/choivxcz/Peso-Pilot-App#installation-and-setup).

## Author

Karl Sebastian V. Cuerdo
