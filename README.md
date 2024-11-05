# Weather App 🌤️

A comprehensive Weather App built with Flutter that brings real-time weather updates to your fingertips. Using the OpenWeatherMap API, this app displays accurate and up-to-date information for your specific location, including temperature, weather conditions, sunrise and sunset times, and more. The user interface is crafted for a visually pleasing experience, showing clear, concise weather details at a glance.

Designed with mobile devices in mind, this app utilizes Flutter's powerful cross-platform capabilities, making it run smoothly on both Android and iOS devices. It leverages the device's location services, ensuring that you always get the most relevant and localized weather information. This project is a great example of combining multiple Flutter dependencies for geolocation, state management, and data handling, showcasing the power of Flutter for building modern, user-friendly mobile applications.

Whether you’re a Flutter enthusiast looking to expand your knowledge, or someone who needs a weather app tailored to precise location tracking, this project provides an excellent foundation to work from and build upon.

##App Screenshot ![Screenshot_20241105_221339](https://github.com/user-attachments/assets/3dd62836-29da-40aa-a381-c0ca6545ab8a)


## Features
- **Real-Time Weather Data**: Get the latest weather updates, including temperature, conditions (like clear, cloudy, rainy), and daily high/low temperatures.
- **Sunrise and Sunset Times**: Displays accurate times for sunrise and sunset based on your location.
- **Location-Based Data**: Automatically detects and tracks your location for precise weather updates.
- **Simple, Intuitive UI**: Designed with a clean and bright interface for ease of use and clarity.
- **Built with Flutter**: Cross-platform support makes it compatible with both Android and iOS devices.

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

## Setup

1. Add your OpenWeatherMap API key in the app:
- Open lib/constants.dart or the appropriate file where API keys are managed.
- Replace "YOUR_API_KEY" with your actual OpenWeatherMap API key.

## Running the App
Run the following command to launch the app on a connected device or emulator:

### Note
This app requires location permission to function. Make sure to grant location permissions when prompted.

