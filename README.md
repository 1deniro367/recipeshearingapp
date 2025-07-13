# Recipe Sharing App

A beautiful Flutter app for sharing and discovering recipes with mock backend.

## Features

- 🔐 **Authentication**: Email/password login and registration
- 📱 **Recipe Management**: Create, view, edit, and delete recipes
- 🔍 **Search & Filter**: Search recipes by title, description, or category
- 👤 **User Profiles**: View user information and created recipes
- 📱 **Responsive Design**: Works on web, mobile, and desktop

## Project Structure

```
lib/
├── main.dart                 # App entry point
├── models/
│   ├── user_model.dart      # User data model
│   └── recipe_model.dart    # Recipe data model
├── services/
│   ├── auth_service.dart    # Mock auth service
│   └── recipe_service.dart  # Mock recipe service
├── prodivers/
│   └── auth_provider.dart   # State management for auth
└── screens/
    ├── auth_screen.dart     # Login/Register screen
    ├── home_screen.dart     # Main recipe list
    ├── recipe_detail_screen.dart # Recipe details
    ├── add_recipe_screen.dart   # Create recipe
    └── profile_screen.dart  # User profile
```

## Getting Started

### Prerequisites

- Flutter SDK (latest stable version)
- Dart SDK

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd recipeshearingapp
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## Features in Detail

### Authentication
- Email/password registration and login
- Secure user session management
- Profile management

### Recipe Management
- Create new recipes with ingredients and instructions
- View recipe details with step-by-step instructions
- Search and filter recipes by category
- User-specific recipe collections

### User Interface
- Modern Material Design 3
- Responsive layout for all screen sizes
- Beautiful recipe cards with ratings
- Intuitive navigation

## Dependencies

- `provider`: State management
- `cupertino_icons`: iOS style icons

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is licensed under the MIT License.

## Support

If you encounter any issues or have questions, please open an issue on GitHub.
