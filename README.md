## Name : Lokesh Shukla

## Roll Number : 23EACCA033

## Experiment Title : RSS Feed Reader (Flutter)

## Aim : To develop a Flutter application that fetches and displays RSS feed data from the internet.

## Procedure

- Install Flutter SDK
  - Download and install the Flutter SDK from the official website and set up environment variables.
  - Verify installation using:
    ```bash
    flutter doctor
    ```

- Install Android Studio
  - Install Android Studio and configure it with the Flutter and Dart plugins.

- Create a New Flutter Project
  - Open Android Studio
  - Click on New Flutter Project
  - Select Flutter Application
  - Enter project name and location
  - Click Finish

- Add HTTP Dependency
  - Open `pubspec.yaml`
  - Add the following dependency:
    ```yaml
    http: ^1.6.0
    ```
  - Run:
    ```bash
    flutter pub get
    ```

- Write the Source Code
  - Open the main.dart file and replace the existing code with the given program.
  - The program uses the http package to fetch data from an online API:
    https://jsonplaceholder.typicode.com/posts/1

- Connect Device/Emulator
  - Start an Android emulator or
  - Connect a physical Android device with USB debugging enabled

- Run the Application
  - Click the Run button or use the command:
    ```bash
    flutter run
    ```

- Observe the Output
  - The app fetches JSON data from the API
  - Displays:
    - An AppBar with title “RSS Page”
    - API response displayed as text on screen

## Output: A screen displaying fetched JSON data from the API with an AppBar titled 'RSS Page'.

- <img width="1919" height="1031" alt="Screenshot 2026-04-14 191428" src="https://github.com/user-attachments/assets/18ae4393-e8b4-4466-8335-5cff2869e5a1" />

## Conclusion : The experiment was successfully completed by fetching data from a web API using the HTTP package in Flutter and displaying it dynamically in the application.
