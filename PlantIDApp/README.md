# PlantID Android Application

This is the PlantID Android application that identifies plants at the taxonomist level. The app works both online and offline.

## Features

- Capture or select plant images
- Identify plants using online API when internet is available
- Identify plants offline using embedded ML model (TensorFlow Lite)
- Display taxonomy details of identified plants
- Modern UI with Material Design components

## Setup

1. Open the project in Android Studio.
2. Build and run the app on an emulator or physical device.
3. Grant camera and storage permissions when prompted.
4. Use the app to capture/select plant images and get identification results.

## Notes

- The app automatically switches between online and offline identification based on network availability.
- The offline model is embedded in the app assets.
- API keys and configuration should be added in the appropriate files.
