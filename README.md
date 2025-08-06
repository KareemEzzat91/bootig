# Bootig - Kuwaiti Designer Mobile App

A modern Flutter mobile application that provides seamless access to the Kuwaiti Designer website with enhanced user experience, custom loading screens, and optimized navigation.

## 📱 Features

- **WebView Integration**: Seamless browsing experience within the app
- **Custom Loading Screens**: Beautiful animated loading screens with Arabic text support
- **Optimized Navigation**: Fast and responsive navigation between pages
- **External Link Handling**: Automatic handling of WhatsApp and phone links
- **Responsive Design**: Optimized for various screen sizes and orientations
- **Arabic Language Support**: Full RTL support and Arabic text display
- **Splash Screen**: Professional app launch experience
- **Error Handling**: Graceful error management and recovery
- **Performance Optimized**: Lightweight and fast loading times

## 📸 Screenshots

<!-- Add your app screenshots here -->
### App Screenshots
<img width="409" height="825" alt="image" src="https://github.com/user-attachments/assets/c93dc3c1-1372-4143-abcb-16f05f5ee690" />
<img width="1011" height="359" alt="image" src="https://github.com/user-attachments/assets/b89e12de-e28e-4167-af80-55175ce01532" />



<!-- You can add more screenshots by uploading them to the assets/images/ directory and referencing them here -->

## 🚀 Installation

### Prerequisites

- [Flutter](https://flutter.dev/docs/get-started/install) (version 3.7.0 or higher)
- [Dart](https://dart.dev/get-dart) (latest stable version)
- [Android Studio](https://developer.android.com/studio) or [VS Code](https://code.visualstudio.com/)
- Android SDK (for Android development)
- Xcode (for iOS development, macOS only)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/bootig.git
   cd bootig
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

## 🏃‍♂️ How to Run the App

### Development Mode
```bash
# Run in debug mode
flutter run

# Run with hot reload
flutter run --hot
```

### Production Build
```bash
# Build for Android
flutter build apk --release

# Build for iOS
flutter build ios --release

# Build for web
flutter build web
```

## 📁 Folder Structure

```
bootig/
├── android/                 # Android-specific files
├── ios/                    # iOS-specific files
├── lib/                    # Main Dart source code
│   ├── main.dart          # App entry point
│   └── widgets/           # Custom widgets
│       └── new.dart       # Main WebView implementation
├── assets/                # App assets
│   └── images/           # Images and icons
├── test/                 # Unit tests
├── pubspec.yaml          # Dependencies and app configuration
└── README.md            # This file
```

## 🛠️ Technologies Used

- **Flutter** - Cross-platform mobile development framework
- **Dart** - Programming language
- **WebView Flutter** - Web content display
- **URL Launcher** - External link handling
- **Shimmer** - Loading animations
- **Flutter Native Splash** - Splash screen generation
- **Rename App** - App renaming utilities

### Key Dependencies

```yaml
dependencies:
  flutter: sdk: flutter
  webview_flutter: ^4.11.0
  url_launcher: ^6.3.1
  shimmer: ^3.0.0
  flutter_native_splash: ^2.4.6
  rename_app: ^1.6.3
```

## 🤝 Contributing

We welcome contributions to improve Bootig! Here's how you can help:

### How to Contribute

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes**
4. **Test your changes**
   ```bash
   flutter test
   flutter analyze
   ```
5. **Commit your changes**
   ```bash
   git commit -m "Add: your feature description"
   ```
6. **Push to the branch**
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Create a Pull Request**

### Code Style

- Follow the [Dart Style Guide](https://dart.dev/guides/language/effective-dart/style)
- Use meaningful variable and function names
- Add comments for complex logic
- Ensure all tests pass before submitting

## 📞 Contact & Developer Info

**Developer**: [Your Name]  
**Email**: [your.email@example.com]  
**GitHub**: [@yourusername](https://github.com/yourusername)  
**LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)

### Project Links

- **Website**: [Kuwaiti Designer](https://kuwaiti-designer.com/)
- **Repository**: [GitHub Repository](https://github.com/yourusername/bootig)
- **Issues**: [Report Issues](https://github.com/yourusername/bootig/issues)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

⭐ **Star this repository if you found it helpful!**
