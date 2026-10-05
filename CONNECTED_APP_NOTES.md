# Food App DEPI - Connected App

This version keeps the existing UI/screens and connects the main application flow with a shared in-memory `AppStore`.

Connected flow:
1. Splash -> Login
2. Login -> Home
3. Sign Up -> Verification -> Home
4. Home -> Restaurant / Food Listing / Search
5. Food Details -> Add to Cart
6. Restaurant/Food Listing quick-add -> Cart
7. Cart -> Payment
8. Payment -> Order creation -> Success
9. Orders reads the same orders state
10. Home menu -> Profile / Orders / Logout
11. Profile personal information and addresses share app state

Notes:
- The project is a local/demo app; there is no real backend, database, payment gateway, or email verification service.
- Cart, orders, profile data, and addresses are kept in memory for the current app session.
- Run `flutter pub get` and then `flutter run`.
