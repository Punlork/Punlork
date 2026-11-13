## Hi, I'm Chek Punlork

Mobile engineer in Phnom Penh, Cambodia (UTC+7). I've spent 4+ years building
iOS and Android apps with Flutter, React Native and Kotlin.

I like apps that keep working when the network doesn't: offline-first data,
sync that never drops a write, and enough tests and CI that shipping is boring.
I also write things down (architecture docs, decision records, clear PRs) so a
team can work with me asynchronously.

- **Now:** leading the mobile architecture of an enterprise loan management app
  in Flutter, used offline by loan officers in the field
- **Open to:** remote mobile engineering roles

### Featured work

**[Jabhouy](https://github.com/Punlork/Jabhouy)**: offline-first shop management app (Flutter)

- Inventory, sales and customer loans for small shops, in Khmer and English
- Pub workspace of six packages, with an outbox sync engine in pure Dart:
  every change saves to SQLite at once and reaches the server on reconnect,
  with retry and backoff
- 400+ automated tests: unit, BLoC, widget, Drift migration and Patrol
  integration tests
- GitHub Actions on every PR; merges to main build a signed APK with Fastlane
  and publish a release
- Kotlin `NotificationListenerService` bridged to Flutter to read bank
  notifications for income tracking
- Documented in an [architecture guide](https://github.com/Punlork/Jabhouy/blob/main/ARCHITECTURE.md)
  and decision records

**[flutter_runtime_debugger](https://pub.dev/packages/flutter_runtime_debugger)**: on-device debugger for Flutter apps (pub.dev package)

- Inspect logs, network, BLoC state, crashes, FPS, routes and local storage
  from an in-app overlay, with no DevTools or USB cable
- Zero dependencies, plugin-based tabs, access tiers per build environment

### Tech

| Area | Tools |
|---|---|
| **Mobile** | Flutter, Dart, React Native, Kotlin |
| **Architecture** | Clean architecture, BLoC, Redux, feature modules, offline-first sync |
| **Data** | Drift/SQLite, REST APIs, Firebase |
| **Testing** | Unit, widget, BLoC, Patrol integration tests |
| **Release** | GitHub Actions, Jenkins, Fastlane, TestFlight, Firebase App Distribution |
| **Also** | Vue 3, Figma |

### Contact

[LinkedIn](https://www.linkedin.com/in/punlork-chek-a29740217) ·
[pub.dev](https://pub.dev/packages/flutter_runtime_debugger)
