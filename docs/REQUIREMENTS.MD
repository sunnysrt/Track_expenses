REQUIREMENTS
_________________

# Required Tools, Software, Dependencies, Debuggers, and Testing Platforms

_Comprehensive list for the Track Expenses project (as of April 2025). All versions are compatible with each other and the Flutter/Dart/Isar/Riverpod stack targeting Android and Web._

---

## 1. Core Tools & Software

| Tool/Software           | Latest Version (Apr 2025) | Purpose                                 | Compatibility Notes                |
|------------------------ |-------------------------- |-----------------------------------------|------------------------------------|
| **Flutter SDK**         | 3.22.x                    | Main cross-platform framework           | Compatible with Dart 3.x           |
| **Dart SDK**            | 3.4.x                     | Programming language                    | Required by Flutter 3.22.x         |
| **VS Code**             | 1.91.x                    | IDE                                     | Flutter/Dart plugins available     |
| **Android Studio**      | Hedgehog (2024.1)         | Optional IDE, Android emulator          | Flutter plugin available           |
| **Git**                 | 2.45.x                    | Version control                         | Universal                          |
| **Node.js**             | 20.x (optional)           | For some web build tools                | Only if using web-specific tooling |

---

## 2. Flutter Dependencies (pubspec.yaml)

| Package Name                   | Latest Version (Apr 2025) | Purpose                                         | Compatibility Notes                |
|--------------------------------|-------------------------- |-------------------------------------------------|------------------------------------|
| **isar**                       | 4.0.0                     | Offline database                                | Flutter 3.x, Dart 3.x              |
| **isar_flutter_libs**          | 4.0.0                     | Native bindings for Isar                        | Required for mobile                |
| **riverpod**                   | 3.0.0                     | State management                                | Flutter 3.x, Dart 3.x              |
| **flutter_riverpod**           | 3.0.0                     | Riverpod for Flutter widgets                    | Flutter 3.x                        |
| **file_picker**                | 6.1.1                     | File selection                                  | Android/Web supported              |
| **intl**                       | 0.19.0                    | Currency/date formatting                        | Dart 3.x                           |
| **syncfusion_flutter_pdf**     | 25.1.41                   | PDF text/table extraction                       | Free for non-commercial use        |
| **pdf**                        | 3.12.0                    | PDF generation/parsing (alternative)            | Dart 3.x                           |
| **excel**                      | 3.0.0                     | Read/write Excel files                          | Dart 3.x                           |
| **csv**                        | 6.0.0                     | CSV parsing                                     | Dart 3.x                           |
| **permission_handler**         | 11.3.0                    | Runtime permissions                             | Android 6.0+, Flutter 3.x          |
| **sms_maintained**             | 1.0.5                     | Read SMS (Android only)                         | Android only, not for iOS/Web      |
| **syncfusion_flutter_charts**  | 25.1.41                   | Advanced charts/visualizations                  | Free for non-commercial use        |
| **fl_chart**                   | 0.65.0                    | Alternative charting library                    | Flutter 3.x                        |
| **local_auth**                 | 2.2.0                     | Biometric authentication                        | Android/iOS only                   |
| **flutter_secure_storage**     | 9.0.0                     | Secure local storage                            | Android/iOS/Web                    |
| **cupertino_icons**            | 1.0.8                     | iOS-style icons                                 | Flutter 3.x                        |
| **path_provider**              | 2.1.3                     | File system paths                               | Flutter 3.x                        |

---

## 3. Testing & Debugging

| Tool/Package                  | Latest Version (Apr 2025) | Purpose                        | Compatibility Notes                |
|-------------------------------|-------------------------- |--------------------------------|------------------------------------|
| **flutter_test**              | Bundled                   | Unit/widget/integration tests  | Flutter 3.x                        |
| **mockito**                   | 6.0.0                     | Mocking in tests               | Dart 3.x                           |
| **integration_test**          | 0.12.0                    | End-to-end testing             | Flutter 3.x                        |
| **flutter_lints**             | 4.0.0                     | Linting                        | Dart 3.x                           |
| **Dart DevTools**             | Bundled                   | Debugging, performance         | Flutter 3.x                        |
| **VS Code Flutter/Dart Plugins** | Latest                  | IDE integration                | VS Code 1.91.x                     |

---

## 4. Optional/Advanced

| Tool/Package                  | Latest Version (Apr 2025) | Purpose                        | Compatibility Notes                |
|-------------------------------|-------------------------- |--------------------------------|------------------------------------|
| **json_serializable**         | 6.8.0                     | Code generation for models     | Dart 3.x                           |
| **build_runner**              | 2.4.8                     | Code generation                | Dart 3.x                           |
| **flutter_launcher_icons**    | 0.13.1                    | App icon generation            | Flutter 3.x                        |
| **flutter_native_splash**     | 2.4.0                     | Splash screen                  | Flutter 3.x                        |

---

## 5. Asset Management

- **Image assets**: For bank/merchant logos (PNG/SVG, stored in `assets/`)
- **Fonts**: Custom fonts as needed (Google Fonts recommended)

---

## 6. Compatibility Summary

- **Flutter 3.22.x** and **Dart 3.4.x** are compatible with all listed packages as of April 2025.
- **Isar 4.x** is fully compatible with Flutter 3.x and Dart 3.x.
- **Riverpod 3.x** works seamlessly with Flutter 3.x.
- **Syncfusion** packages require a free community license for non-commercial use.
- **sms_maintained** is Android-only; SMS import will not work on iOS/Web.
- **local_auth** and **flutter_secure_storage** support Android/iOS; web support is limited.
- All charting, parsing, and storage libraries are compatible with the latest Flutter/Dart.

---

## 7. Platform Support

- **Android**: Full support for all features.
- **Web**: Most features supported except SMS reading and some native APIs.
- **iOS**: Most features supported except SMS reading (due to iOS restrictions).

---

## 8. Other Recommendations

- **Sample Data**: Collect sample PDFs, Excels, CSVs, and SMS messages for testing.
- **GitHub/GitLab**: For code hosting and collaboration.
- **Stack Overflow, Flutter Community**: For troubleshooting and support.

---

**Summary:**  
All listed tools and dependencies are compatible with each other as of April 2025. Stick to the latest stable versions, and always check for breaking changes when upgrading. For commercial use of Syncfusion, ensure you have the appropriate license.

---