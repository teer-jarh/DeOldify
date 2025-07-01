# Flutter Grocery Apps

This folder contains simple Flutter applications that demonstrate a small grocery store system using Firebase for realtime updates.

- **user_app**: Allows customers to view products from Firestore, add items to a cart, and place orders.
- **vendor_app**: Enables shop owners to add new products to the `products` collection.
- **admin_dashboard**: Displays orders in realtime for administrative monitoring.

Each app has its own `pubspec.yaml` and a minimal `main.dart` showing how to connect to Firebase.

To run an app, navigate into its directory and use `flutter run`. Make sure you configure Firebase for Android/iOS/Web accordingly.
