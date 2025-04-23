# Indian_language_translator

A comprehensive Indian language translation application built with Flutter and Firebase. This app enables users to translate 30 different indian languages into their language by text and voice with fatching api of google and this is login free application here your translation history saved so you can also use it in ofline.

## Features

### User Authentication
- No user login needed

### Input Management
-user can input data using voice and text
-option of which language user to want to convert in which language

###Special features
-User can see the history of translations
-can favourite any of them or delete any of them
-User can see that translation ofline if that was favourite translation history

### User Experience
- Clean and intuitive user interface
- Dark/Light theme support
- Smooth animations and transitions
- Responsive design for all screen sizes

### Security
- Data of user is till the user
- no other authorities can see the data of user
- it will store in local storage

## Technical Implementation

### Frontend
- Flutter (Dart)
- Material Design components
- Responsive layouts

### Backend
- Firebase Authentication
- Cloud Firestore for data storage
- Secure data encryption

## Dependencies
```yaml
dependencies:
  flutter:
    sdk: flutter
  firebase_core: ^latest_version
  firebase_auth: ^latest_version
  cloud_firestore: ^latest_version
  google_sign_in: ^latest_version
  shared_preferences: ^latest_version
```

## Folder Structure

- `lib/app`: All app theme
- `lib/models`: translation models
- `lib/widgets`: Reusable UI components
- `lib/services`: Firebase and other service integrations

## Installation

1. Clone the repository:
```bash
git clone https://github.com/BhumiPatel2309/e-Journal.git
```

2. Install dependencies:
```bash
flutter pub get
```

3. Configure Firebase:
   - Create a new Firebase project
   - Add your Firebase configuration files
   - Enable Authentication and Firestore

4. Run the app:
```bash
flutter run
```
## Screens
Here are the app's screenshots showcasing various screens:

![Register Screen]()
![Login Screen]()
![Home Screen]()
![Entry Screen]()
![Entry List Screen]()
![Logout Screen]()


## Future Enhancements
- Image's text translation
- PDF or DOC file translation

## Contributors
- [RutujNanavati22it080](https://github.com/RutujNanavati22it080)

## Acknowledgments
- Flutter team for the amazing framework
- Firebase for backend services
- Open-source packages used in this project
