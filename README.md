# Flutter Ebook App

FlutterEbookApp is a cross-platform eBook reading application built with Flutter. It allows users to browse, download, and seamlessly read their favorite books, featuring an integrated EPUB reader and local library management.

## Features

* **Browse & Discover**: Explore a wide variety of free eBooks.
* **Download for Offline Reading**: Download your favorite books and read them anywhere, without an internet connection.
* **Integrated EPUB Reader**: Read books directly within the app using the built-in reader.
* **Dark Mode Support**: Enjoy reading at night with a comfortable dark theme.
* **Cross-Platform**: Works smoothly on Android, iOS, and other platforms.

## Getting Started

To run this project locally, ensure you have Flutter installed. Then, follow these steps:

1. **Clone this repository:**
   ```bash
   git clone https://github.com/ShanailKamran/Ebook_App_Flutter.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd Ebook_App_Flutter
   ```
3. **Get the Flutter dependencies:**
   ```bash
   flutter pub get
   ```
4. **Run the app:**
   ```bash
   flutter run
   ```

## Key Dependencies

* `flutter_riverpod` - State management
* `dio` - Network requests
* `sembast` - Local database for offline storage
* `iridium_reader_widget` - For parsing and rendering EPUB files
