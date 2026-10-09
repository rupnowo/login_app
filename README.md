# Login App

A Flutter app implementing email/password authentication with Firebase: login, registration, and forgot-password screens, an auth gate that routes users based on sign-in state, and a get_user service for fetching the current user's profile data.

**Tech stack:** Flutter / Dart, Firebase (Auth + Firestore)

**How to run:**
```
flutter pub get
flutter run
```
Note: you need a `google-services.json` (Android) / Firebase config with your own project settings before auth will work.

**Status:** Standard auth-tutorial build; solid as a reusable auth scaffold.
