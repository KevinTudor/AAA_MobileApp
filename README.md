# Air Assault Application

## Introduction
The Air Assault Application is a mobile solution developed in response to a Request for Proposal (RFP) from the 101st Airborne Division. It aims to enhance training tools and materials for soldiers pursuing Air Assault, Ranger, and Pathfinder qualifications. This README provides an overview of the project, its goals, and key information.

## Team
- Kevin Tudor
- Alex Chaban
- Renan Queiroz

## Project Timeline
- Start Date: August 2022
- End Date: May 2023

## Task

This project responds to the 101st Airborne Division's RFP by creating a proof-of-concept mobile application. The application serves as a hub for training resources, recent news, and general information related to Air Assault, Ranger, and Pathfinder qualifications.

## Criteria

To meet the project's goals, we aim to:
- Offer easily accessible educational resources for Air Assault, Pathfinder, and Ranger training.
    - News section for any updates to the Air Assault, Pathfinder, and Ranger education modules and currency events.
    - Provide material to study for the Air Assault, Pathfinder, and Ranger qualification tests.
- Distribute the application locally on both iOS and Android devices.

## Technology Stack
The application was built using the following technologies:
- JavaScript
- React Native
- React.js
- Cheerio
- Expo 

## Installation and Usage
To simulate the app for live development testing:
- Create account with Expo https://expo.dev/signup (Optional)
- Clone the repository.
- Open with VS Code and create a new terminal.
    - run "git checkout main" ->  "npm install" (this will update necessary dependency modules).
    - In VS Code terminal run "npx expo login -h" ("whoami" should say your Expo username).
    - Once successfully logged in run "npx expo start".
- Download Expo Go on an iOS or Android device and sign in.
- Scan the QR code with the device.
- Metro Bundler should now be hosting the application through the Expo Go application.

## Current State and Future Plans
The application is currently able to run effectively on Android devices (local or emulated). The application is only available on iOS via live testing on Expo Go as the ".ipa" can not be verified without a Developers License with Apple. In the future the application should be able to run locally on iOS, have profiles to save user progress and have additional course testing pages. Personally, I would like to see this application hosted on the respective mobile stores and push/maintain versions with Expo.
