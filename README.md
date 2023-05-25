# Flutter Jailbreak Detection

Flutter jailbreak and root detection plugin.

It uses RootBeer on Android, and IOSSecuritySuite on iOS.

## Getting Started

   ```
   import 'package:flutter_jailbreak_detection/flutter_jailbreak_detection.dart';

bool jailbroken = await FlutterJailbreakDetection.jailbroken;
bool developerMode = await FlutterJailbreakDetection.developerMode; // android only.
   ```


