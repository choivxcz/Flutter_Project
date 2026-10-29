# flutter_try

My Flutter practice repository: experiments with layouts, navigation, authentication, and Firebase while learning Flutter and Dart.

> **Peso Pilot**, the AI-powered finance app that started here as my final project (`lib/final_project/`), now has its own repository: **[Peso-Pilot-App](https://github.com/choivxcz/Peso-Pilot-App)**. Go there for the latest version and setup instructions.

## What's inside

```
lib/
  final_project/   Original copy of Peso Pilot (kept for history)
  pages/           Practice screens: welcome, sign-in, profile, navigation, animations
  widgets/         Reusable practice widgets (navbar, drawer)
api/               Serverless proxy used by Peso Pilot's AI chat
functions/         Firebase Functions version of the same proxy
python-practice/   Small Python exercises from class (loops, lists, file storage)
```

## Run it

```bash
flutter pub get
flutter run --dart-define=OPENROUTER_BACKEND_URL=https://your-project.vercel.app/api
```

The AI chat needs the proxy in `api/` deployed with an `OPENROUTER_API_KEY` environment variable. See the [Peso-Pilot-App README](https://github.com/choivxcz/Peso-Pilot-App#run-it) for details.

---

Built by [Karl Cuerdo](https://github.com/choivxcz).
