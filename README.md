Jobizz Mobile Application
Overview
Jobizz is a mobile application designed to help users find and apply for jobs easily. It provides a user-friendly interface for browsing featured and popular job listings, and allows users to search for specific job positions. The app is built using React Native and leverages various libraries like Expo for enhanced development.

Features
Login Screen: Allows users to log in by entering their name and email.
Homepage: Displays user profile, search bar, and lists of featured and popular job listings.
Job Listings: Each job listing includes details like job title, company, salary, and location. Featured jobs have an enhanced visual style with background images.
Project Structure
css
.
├── App.js
├── assets
│   ├── fonts
│   │   ├── PoppinsRegular-B2Bw.otf
│   │   ├── PoppinsMedium-1JPv.otf
│   │   ├── PoppinsSemibold-8l8n.otf
│   │   └── PoppinsBold-GdJA.otf
│   ├── apple_icon.png
│   ├── google_icon.png
│   ├── facebook_icon.png
│   ├── ellipse-798.png
│   ├── ellipse.png
│   ├── search1-1.png
│   ├── filter5.png
│   ├── blue3.jpeg
│   ├── mask-group.png
│   ├── mask-group1.png
│   ├── facebook_icon.png
│   ├── microsoft.png
│   ├── google_icon.png
│   ├── adobe.png
│   ├── twitter.png
│   ├── burgerking.png
│   ├── image-8.png
│   ├── sign.png
│   ├── apple_icon.png
│   ├── canva.jpg
├── screens
│   ├── LoginScreen.js
│   └── Homepage.js
└── README.md
Installation and Setup
Clone the repository:

sh
git clone https://github.com/yourusername/jobizz.git
cd jobizz
Install dependencies:

sh
npm install
Start the Expo server:

sh
expo start
Run on a device:

Use the Expo Go app on your phone to scan the QR code.
Or, run on an emulator using the commands provided in the Expo interface.
Usage
Login: Enter your name and email to log in.
Browse Jobs: Scroll through featured and popular job listings on the homepage.
Search Jobs: Use the search bar to find specific job positions.
View Job Details: Tap on any job listing to see more details.
Customization
Add New Jobs: Update the featuredJobs and popularJobs arrays in Homepage.js to add new job listings.
Change Fonts: Add new font files to the assets/fonts directory and update the useFonts hook in App.js.
Modify Styles: Adjust styles in the StyleSheet.create method within each screen component file to customize the look and feel.
Dependencies
React Native
Expo
@react-navigation/native
@react-navigation/native-stack
expo-font
Author
Name: Gyabaah Felix
ID: 11227253