# PitStop

PitStop is a Flutter vehicle care app designed to help drivers manage vehicle details, reminders, maintenance, expenses, and support features in one place.

## What this app includes

- splash and onboarding flow
- login, sign-up, and forgot password screens
- home dashboard for quick vehicle actions
- profile, notifications, and settings
- premium section and demo AI assistant
- document and vehicle care UI

## Tech stack

- Flutter
- Dart
- Material 3 UI
- Route-based navigation

## Project structure

```text
PitStop-main/
├── README.md
├── main.dart
├── Screens/
│   ├── ai_chat.dart
│   ├── documents.dart
│   ├── forgot_password.dart
│   ├── home.dart
│   ├── login.dart
│   ├── notifications.dart
│   ├── onboarding.dart
│   ├── premium.dart
│   ├── profile.dart
│   ├── settings.dart
│   ├── sign_up.dart
│   └── splash.dart
└── widgets/   # referenced in the app and may be added later
```

## Notes

This project is currently a UI prototype with a clean app flow, but some files referenced in `main.dart` are not present in the workspace yet. The app is still in progress and is intended to grow as more team members contribute.

## Getting started

```bash
flutter --version
flutter pub get
flutter run
```

## Team contribution format

Each contributor can add a small section in the same style:

```md
## <Feature Name>

### Contributor
- Name:
- Role:

### Description
Short summary of the feature.

### Status
In progress / Completed / Planned
```

This keeps the README polished and consistent even when multiple people contribute.

## License

No license file is currently included in the project.
