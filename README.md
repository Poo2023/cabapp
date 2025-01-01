Cab Application 🚖

A modern cab booking application developed using Flutter and Firebase. This project leverages Flutter’s cross-platform capabilities and Firebase’s robust backend services to create a seamless experience for users and drivers.

Features 🌟

User Authentication:

Login and Registration via email and password.

Password recovery feature.

Real-Time Location Tracking:

Retrieve and track user’s current location.

Integration with Google Maps for location services.

Booking System:

Easy cab booking interface.

Manage bookings with real-time status updates.

Payment Integration:

In-app payment functionality (basic structure in place).

User-Friendly Interface:

Intuitive screens for login, signup, and home functionality.

Splash screen for branding and better user experience.

Custom Widgets:

Modular widgets for location tracking, payments, and more.

Tech Stack 🛠️

Frontend: Flutter (Dart)

Backend: Firebase (Authentication, Realtime Database, Firestore)

APIs: Google Maps API for geolocation

State Management: Basic stateful and stateless widget usage

Folder Structure 📂

lib/
├── helper/           # Utility classes for networking and response handling
├── screens/          # Individual screen implementations
├── widgets/          # Reusable widget components
└── main.dart         # Application entry point

Key Files:

lib/main.dart: Application entry point.

lib/screens/home_screen.dart: Home screen UI and logic.

lib/screens/login_screen.dart: User login functionality.

lib/screens/signup_screen.dart: User registration functionality.

lib/screens/location_getter.dart: Fetch and display user location.

lib/widgets/location_tracker.dart: Widget for tracking location.

Prerequisites 📋

Install Flutter SDK: Flutter Installation Guide.

Set up a Firebase Project:

Enable Authentication (Email/Password).

Configure Firestore Database.

Download google-services.json and place it in android/app/.

Obtain an API Key for Google Maps Platform.

Setup Instructions 🚀

Clone the repository:

git clone <repository-url>
cd cabapp-main

Install dependencies:

flutter pub get

Add Firebase Configurations:

Place google-services.json in android/app/.

Run the application:

flutter run

Future Enhancements 🚧

Integrate ride-sharing functionality.

Add driver-specific modules.

Enhance payment system with third-party payment gateways.

Develop an admin dashboard for managing users and bookings.

Optimize for performance and add more animations.

Screenshots 📸

Include screenshots of the application’s key screens (home, login, booking, etc.).

Contributions 🤝

Contributions are welcome! To contribute:

Fork the repository.

Create a feature branch:

git checkout -b feature-name

Commit your changes:

git commit -m "Add some feature"

Push to the branch:

git push origin feature-name

Open a pull request.
