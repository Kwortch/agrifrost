# agrifrost
AgriFrost is an IoT-based smart farming application designed to help farmers monitor soil moisture and environmental conditions in cold-climate farms such as strawberry farms in Baguio. The system uses sensors to collect real-time data including soil moisture, temperature, and humidity levels.


# AgriFrost Project

Application Description

Technologies Used

Flutter
IoT
Cloud Computing (Google Cloud/Firebase)


Features

Real-time soil moisture monitoring
Temperature and humidity monitoring
Irrigation recommendations
Moisture risk alerts
Mobile notifications
Farm monitoring dashboard
Historical data logs


Installation Instructions
Install Flutter SDK on your computer.
Install Android Studio or VS Code with Flutter and Dart plugins.
Clone the project repository from the provided source.
Open the project folder in your chosen IDE.
Run 'flutter pub get' to install dependencies.
Connect an Android emulator or physical device.
Run 'flutter run' to launch the application


Setup

Set up the ESP32/Arduino board with the soil moisture sensor, DHT11/DHT22 sensor, relay module, and optional water pump.
Program the ESP32/Arduino to connect to Wi-Fi and transmit sensor data to the Firebase Realtime Database.
Create a Firebase project and configure the Realtime Database for cloud data storage.
Develop and test the Flutter mobile/web application for real-time monitoring and alerts.
Test communication between the IoT device, Firebase database, and the application dashboard.
Initialize the system securely and perform a test monitoring and irrigation cycle.
