# AgroRover Task TODO

## Goals
1. Add two IP address fields in Profile tab (Rover IP + Camera IP)
2. Make the whole app switch language when a language is selected
3. Fix runtime provider exception in Rover Control capture button

## Steps
- [x] Add translation keys to `app_translations.dart` (home stats, alerts, profile sections, connection, account, edit-profile)
- [x] Wire `MaterialApp` locale in `main.dart` for app-wide language
- [x] Translate `home_tab.dart` (stats, alerts, farm name)
- [x] Translate `profile_tab.dart` + add Camera IP field
- [x] Fix provider exception in `rover_control_tab.dart` `_toggleCapture`
- [x] Verify with `flutter pub get`
- [x] Verify with `flutter analyze` (No issues found)
- [x] Verify with `flutter build apk --debug` (APK built successfully)
