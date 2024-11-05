# Weather App 🌤️

A Flutter-powered Weather App that provides real-time weather updates for your precise location. This app uses the OpenWeatherMap API to fetch live weather data and displays it in a simple, visually appealing UI.

![App Screenshot]![Screenshot_20241105_221339](https://github.com/user-attachments/assets/fa2787ee-96ec-4a38-a1f4-b945d8b16082)

## Features
- **Real-Time Weather Data**: Shows current temperature, weather conditions, and clear indicators for sunrise and sunset times.
- **Precise Location Tracking**: Uses the device's location services to fetch data specific to your location.
- **Smooth User Interface**: Designed with a vibrant and clear UI to enhance user experience.

## Dependencies
The app uses the following dependencies:
- **[geolocator: ^13.0.1](https://pub.dev/packages/geolocator)** - For accessing device location.
- **[weather: ^3.1.1](https://pub.dev/packages/weather)** - To fetch weather data from OpenWeatherMap.
- **[intl: ^0.19.0](https://pub.dev/packages/intl)** - For date formatting.
- **[flutter_bloc: ^8.1.6](https://pub.dev/packages/flutter_bloc)** - For state management.
- **[equatable: ^2.0.5](https://pub.dev/packages/equatable)** - For value comparison in BLoC.

## Getting Started
To run this app locally, follow these steps:

### Prerequisites
- Flutter SDK installed on your machine.
- An OpenWeatherMap API key. [Sign up here](https://home.openweathermap.org/users/sign_up) to get a free API key.
### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app-flutter.git

2. Navigate to the project directory:
   ```bash
   cd weather-app-flutter
   
4. Install dependencies:
   ```bash
     flutter pub get

### Setup

1. Add your OpenWeatherMap API key in the app:
- Open lib/constants.dart or the appropriate file where API keys are managed.
- Replace "YOUR_API_KEY" with your actual OpenWeatherMap API key.

### Running the App
Run the following command to launch the app on a connected device or emulator:

### Note
This app requires location permission to function. Make sure to grant location permissions when prompted.

