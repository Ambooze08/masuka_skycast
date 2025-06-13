# 🌤️ Masuka SkyCast

**Masuka SkyCast** is a sleek Flutter Android & IOS weather app that fetches real-time weather forecasts and presents them in an elegant UI. Built with simplicity and performance in mind, it leverages modern Flutter practices and API integration for a smooth user experience.

---

## 🚀 Features

- ⛅ Real-time weather updates using OpenWeatherMap API
- 🧠 Smart forecast UI with icons and detailed info
- 🔐 Secure API key management via `secrets.dart`
- 📱 Clean, responsive Flutter UI
- 🌙 Light/Dark mode support
- 🔥 Future-ready for Firebase integration

---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/51f7c0c7-e510-4230-abeb-ef18f50bfa94)

Masuka_SkyCast App logo

![image](https://github.com/user-attachments/assets/c1032744-1e19-4509-9a8b-d2884181a245)

reload function 

![image](https://github.com/user-attachments/assets/57a6b33f-bfc3-4356-b042-e2ee3483a7f4)

Everything showing perfect.

---

## 🛠️ Tech Stack

- **Flutter**
- **Dart**
- **OpenWeatherMap API**
- **Firebase** (planned)
- **Custom Widgets & UI Components**

---

## 📦 Installation

```bash
git clone https://github.com/Ambooze08/masuka_skycast.git
cd masuka_skycast
flutter pub get
flutter run
```

---

## 🔑 Setup

1. Create a `secrets.dart` file inside `lib/` with your API key:
```dart
const openWeatherAPIKey = 'YOUR_API_KEY_HERE';
```

2. Add it to `.gitignore` to keep your API key safe:
```
lib/secrets.dart
```

---

## 📁 File Structure

```
lib/
├── main.dart                  # App entry point
├── masuka_screen.dart        # Main UI screen
├── weather_forecast.dart     # Weather data logic
├── additional_info_item.dart # Reusable weather info widget
└── secrets.dart              # API key (excluded from Git)
```

---

## 📌 Todo / Improvements

- Add hourly/daily weather charts
- Implement location search
- Add settings screen with dark/light toggle
- Firebase authentication or analytics
- Unit tests & better error handling

---

## 🧑‍💻 Author

Made with ❤️ by [Ambooze08](https://github.com/Ambooze08)

---

## 📄 License

MIT License. See [LICENSE](LICENSE) for details.
