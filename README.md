# Smart Queue

A modern, Flutter-based mobile application designed to streamline queue management, reduce waiting times, and organize service ticketing efficiently.

## ✨ Features
- 🎫 **Digital Token Generation:** Easily book and generate queue tokens for different services.
- ⏱️ **Real-Time Queue Tracking:** View live queue status, current serving number, and estimated waiting time.
- 🗂️ **Sub-Service Categorization:** Organized service selection with dedicated sub-service screens.
- 📋 **Queue Details & Management:** Detailed view of active bookings, token status, and queue updates.
- ⚡ **Smooth State Management:** Fast and responsive UI updates powered by Provider architecture.
- ☁️ **Firebase Integration:** Connect the application to Firebase services for real-time data handling.
- 🎨 **User-Friendly Interface:** Simple, clean, and intuitive mobile design built with Flutter.

## 🛠️ Tech Stack & Tools
- **Framework:** Flutter
- **Language:** Dart
- **State Management:** Provider
- **Backend / Database:** Firebase
- **IDE & Tools:** Android Studio, Git, GitHub

## 🚀 How to Run the App Locally

### Prerequisites
- Flutter SDK
- Dart SDK
- Android Studio or VS Code
- Android Emulator or physical device
- Git

### Steps

**1. Clone the repository**
```bash
git clone https://github.com/ramreddypulusu/smart_queue_app.git
```
**2. Open the project folder**
Bash
```
cd smart_queue_app
```
**3. Install dependencies**

Bash
```
flutter pub get
```
**4. Configure Firebase**

Set up your own Firebase project and configure the Android app using the appropriate Firebase configuration files.

**5. Run the application**

Bash
```
flutter run
```
<h2>📁 Project Structure</h2>

<pre>
smart_queue_app/
├── android/
├── ios/
├── lib/
│   ├── providers/
│   │   └── queue_provider.dart
│   ├── screens/
│   │   ├── home_screen.dart
│   │   ├── sub_services_screen.dart
│   │   └── queue_detail_screen.dart
│   └── main.dart
└── pubspec.yaml
</pre>

## 🎯 Project Objective
The objective of Smart Queue is to make queue management easier, improve real-time access to token status and waiting times, and help users and service providers monitor and manage queues efficiently.

## 👨‍💻 Developed With
Flutter • Dart • Firebase • GitHub
