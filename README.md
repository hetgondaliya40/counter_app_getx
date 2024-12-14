# Counter App (using GetX)

This project is a simple **Counter App** built using Flutter. It is designed for study purposes and showcases the use of **GetX** for state management. Additionally, it supports responsive design and demonstrates the integration of multiple Flutter dependencies.

## Features

- **Responsive UI:** Built to adjust seamlessly to various screen sizes using `flutter_screenutil`.
- **State Management:** Managed using **GetX**, ensuring a clean and efficient architecture.
- **Modern Fonts:** Styled with Google Fonts for a visually appealing look.
- **Persistent Data:** Includes `shared_preferences` to save and retrieve data locally.
- **HTTP Integration:** Demonstrates the use of the `http` package for API interactions.
- **Extendable:** Built to allow easy addition of future features like attaching more data and creating beautiful counters dynamically.

## Mentor

This project is guided and mentored by **Jaynesh Srakar**.

## Dependencies

This project makes use of the following Flutter packages:

1. [get](https://pub.dev/packages/get) - State management and navigation.
2. [provider](https://pub.dev/packages/provider) - Dependency injection.
3. [google_fonts](https://pub.dev/packages/google_fonts) - Custom fonts.
4. [http](https://pub.dev/packages/http) - API communication.
5. [shared_preferences](https://pub.dev/packages/shared_preferences) - Persistent local storage.
6. [flutter_screenutil](https://pub.dev/packages/flutter_screenutil) - Responsive design.

Make sure to add these dependencies to your `pubspec.yaml` file.

```yaml
dependencies:
  flutter:
    sdk: flutter
  get: ^4.6.5
  provider: ^6.1.3
  google_fonts: ^3.0.1
  http: ^0.15.0
  shared_preferences: ^2.0.15
  flutter_screenutil: ^5.8.4
```

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/counter-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd counter-app
   ```

3. Install the dependencies:

   ```bash
   flutter pub get
   ```

4. Run the app:

   ```bash
   flutter run
   ```

## Project Structure

The app follows a clean architecture approach:

```
lib/
├── controllers/
│   └── counter_controller.dart
├── views/
│   ├── home_view.dart
│   └── counter_view.dart
├── utils/
│   └── constants.dart
├── main.dart
```

- **`controllers/`**: Contains GetX controllers for state management.
- **`views/`**: Includes all the UI components of the app.
- **`utils/`**: Holds reusable utilities like constants or helper functions.

## UI Preview

The app UI is simple yet modern, leveraging the power of `flutter_screenutil` for responsiveness and `google_fonts` for styling. It serves as a base for further enhancements like dynamic data-driven counters.

## Contributing

If you'd like to contribute, feel free to submit a pull request or raise an issue. Contributions are always welcome!

## License

This project is open-source and available under the [MIT License](LICENSE).

---

Happy Coding! 🚀
