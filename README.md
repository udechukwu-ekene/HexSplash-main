### HexSplash-main
HexSplash-main is a React Native project designed to provide a seamless splash screen experience for mobile applications. It leverages animations and custom design to enhance user engagement during the app loading phase.

### Features
Customizable Splash Screen: Easily modify the splash screen design to match your app’s branding.
Smooth Animations: Utilizes React Native animations for a fluid user experience.
Cross-Platform Support: Works seamlessly on both iOS and Android devices.

### Installation
To get started with HexSplash-main, follow these steps:

Clone the repository:

git clone https://github.com/udechukwu-ekene/HexSplash-main.git
cd HexSplash-main

### Install dependencies:
npm install

### Link dependencies (if necessary):
npx react-native link

### Usage
After installation, you can run the project on your emulator or physical device:

### For iOS:
npx react-native run-ios

### For Android:
npx react-native run-android

### Configuration
You can customize the splash screen by editing the src/config.js file. Here are some options you can configure:

### Background Color: Set the background color of the splash screen.
### Logo: Change the logo image used in the splash screen.
### Animation Duration: Adjust the duration of the splash animation
Example configuration in src/config.js:

export default {
  backgroundColor: '#ffffff',
  logo: require('./assets/logo.png'),
  animationDuration: 2000,
};

Contributing
We welcome contributions to HexSplash-main! If you have an idea or find a bug, please open an issue or submit a pull request.

### To contribute:

Fork the repository.
Create a new branch: git checkout -b my-feature.
Make your changes.
Commit your changes: git commit -m 'Add some feature'.
Push to the branch: git push origin my-feature.
Open a pull request.




