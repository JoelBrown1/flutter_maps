# flutter_maps

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

### Update geo.API.Key
- in ios/Runner/AppDelegate.swift -> GMSServices.provideAPIKey
- in android/app/src/main/AndroidManifest.xml 
```
  <meta-data
     android:name="com.google.android.geo.API_KEY"
     android.value="" />
